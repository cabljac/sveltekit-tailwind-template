<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>

<Header />

<main class="w-full h-full">
	<slot />
</main>

<footer />
