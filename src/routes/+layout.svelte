<script>
	import { page } from "$app/stores";
    import Header from "$lib/header.svelte";
	import Footer from "$lib/footer.svelte";
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
    <title>{$page.data.title || 'Svelte Demo'} </title>
</svelte:head>

<Header />

{@render children()}

<Footer />