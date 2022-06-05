<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>

<Header />

<main class="flex flex-1 flex-col p-2 w-full max-w-screen-lg mx-auto box-border">
	<slot />
</main>

<footer class="flex flex-col px-0 md:px-10 py-10 items-center justify-center">
	<p>visit <a class="font-bold" href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>
