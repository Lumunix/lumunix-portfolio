<script>
    import { AppBar } from '@skeletonlabs/skeleton';
    import { LightSwitch } from '@skeletonlabs/skeleton';
    import { fly } from 'svelte/transition';
    import Hamburger from 'svelte-hamburger';
    import routes from '$lib/NavRoutes';

    let open = false;

    function closeNav() {
        open = false;
    }
</script>

<AppBar class="font-bold relative z-10" gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
    <!-- Hamburger Icon -->
    <svelte:fragment slot="lead">
       <Hamburger {open} on:click={() => open = !open} />
    </svelte:fragment>
    Dylan Poljak
    <svelte:fragment slot="trail">
        <LightSwitch />
    </svelte:fragment>
</AppBar>

<!-- Dropdown Menu -->
{#if open}
    <div
        class="absolute left-0 w-full bg-white dark:bg-gray-800 shadow-lg z-50"
        transition:fly={{ y: -100, duration: 300 }}
        style="z-index: 5;">
        <nav class="flex flex-col border-b border-gray-300 dark:border-gray-700">
            {#each routes as route}
                <a
                    href={route.href}
                    class="font-bold px-4 py-2 text-gray-700 dark:text-gray-200 hover:bg-gray-100 dark:hover:bg-gray-700"
                    on:click={closeNav}
                >
                    {route.label}
                </a>
            {/each}
        </nav>
        <div class="flex justify-center gap-4 py-4">

        </div>
    </div>
{/if}


<style>

</style>