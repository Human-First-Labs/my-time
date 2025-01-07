<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import { SkeletonText } from 'carbon-components-svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<SkeletonText paragraph>
		This is a test
	</SkeletonText>

	<Counter />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
</style>
