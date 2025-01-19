<script>
    import { AppBar } from '@skeletonlabs/skeleton';
    import { LightSwitch } from '@skeletonlabs/skeleton';
    import routes from '$lib/NavRoutes';
</script>


<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">

	<svelte:fragment slot="lead">(icon)</svelte:fragment>
	Dylan Poljak
	<svelte:fragment slot="trail">
	<LightSwitch />
	</svelte:fragment>

</AppBar>