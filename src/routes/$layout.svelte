<script lang="ts">
	import '../app.css';
</script>

<svelte:head>
	<link rel="shortcut icon" href="/favicon.png" />
</svelte:head>

<main>
	<slot />
</main>

<style>
	main {
		position: relative;
		max-width: 980px;
		padding: 2em;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>
