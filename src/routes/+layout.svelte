<script>
	export let data;
</script>

<nav>
	<li><a data-sveltekit-preload-data href="/">Home</a></li>
	<li><a data-sveltekit-preload-data href="contact">Contact</a></li>
	<li><a data-sveltekit-preload-data href="about">About</a></li>
</nav>
<h1>{data.name}</h1>
<main>
	<slot />
</main>
