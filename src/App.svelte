<script>
	// Imports
	import { MaterialApp } from 'svelte-materialify';
	
	// Props
	export let name;

	let theme = 'dark';
</script>

<MaterialApp>
	<h1 class="text-center">Hello {name}!</h1>
	<p class="text-center">Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</MaterialApp>

<style>
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>