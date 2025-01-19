<script>
    import { AppBar } from '@skeletonlabs/skeleton';
    import { LightSwitch } from '@skeletonlabs/skeleton';
    import { modeCurrent } from '@skeletonlabs/skeleton';
    import { Hamburger } from 'svelte-hamburgers';
    import routes from '$lib/NavRoutes';
    let open;
</script>

<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
    <!-- Hamburger Icon -->
    <svelte:fragment slot="lead">
        <Hamburger bind:open --color=rgba(var(--theme-font-color-base)/>
    </svelte:fragment>
    Dylan Poljak
    <svelte:fragment slot="trail">
        <LightSwitch />
    </svelte:fragment>
</AppBar>

<!-- Dropdown Menu -->
{#if open}
    <div class="absolute left-0 w-full bg-white dark:bg-gray-800 shadow-lg z-50">
        <nav class="flex flex-col border-b border-gray-300 dark:border-gray-700">
            {#each routes as route}
                <a
                    href={route.path}
                    class="px-4 py-2 text-gray-700 dark:text-gray-200 hover:bg-gray-100 dark:hover:bg-gray-700"
                >
                    {route.name}
                </a>
            {/each}
        </nav>
        <div class="flex justify-center gap-4 py-4">
            <a
                href="https://www.linkedin.com/in/dpoljak/"
                target="_blank"
                class="text-gray-700 dark:text-gray-200 hover:text-blue-500"
                aria-label="LinkedIn"
            >
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="currentColor"
                    class="w-6 h-6"
                >
                    <path
                        d="M4.98 3.5C4.98 2.67 5.63 2 6.5 2s1.52.67 1.52 1.5C8.02 4.33 7.37 5 6.5 5S4.98 4.33 4.98 3.5zM3 8.25V21h5V8.25H3zM10 8.25V21h5v-6.75c0-2.95 4-3.18 4 0V21h5V12c0-7.41-8-7.22-8 0v-3.75h-6z"
                    />
                </svg>
            </a>
            <a
                href="https://github.com"
                target="_blank"
                class="text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400"
                aria-label="GitHub"
            >
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="currentColor"
                    class="w-6 h-6"
                >
                    <path
                        d="M12 0C5.37 0 0 5.37 0 12c0 5.3 3.438 9.8 8.205 11.385.6.113.82-.263.82-.582 0-.288-.01-1.05-.015-2.062-3.338.725-4.042-1.614-4.042-1.614-.546-1.385-1.333-1.754-1.333-1.754-1.09-.744.083-.729.083-.729 1.204.086 1.837 1.237 1.837 1.237 1.07 1.835 2.807 1.304 3.492.997.108-.775.418-1.305.76-1.604-2.665-.303-5.466-1.334-5.466-5.933 0-1.31.47-2.38 1.236-3.222-.124-.303-.535-1.524.118-3.176 0 0 1.008-.322 3.3 1.23.957-.266 1.984-.399 3.005-.404 1.02.005 2.048.138 3.005.404 2.29-1.552 3.296-1.23 3.296-1.23.656 1.652.245 2.873.12 3.176.77.842 1.236 1.913 1.236 3.222 0 4.61-2.807 5.625-5.479 5.922.43.372.814 1.102.814 2.222 0 1.605-.015 2.898-.015 3.291 0 .323.216.7.824.582C20.565 21.796 24 17.297 24 12 24 5.37 18.63 0 12 0z"
                    />
                </svg>
            </a>
        </div>
    </div>
{/if}
