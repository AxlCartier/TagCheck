<script>
	let { children, title } = $props();
	import "/static/app.css";
	import Footer from "../components/Footer.svelte";
	import NavBar from "../components/NavBar.svelte";
</script>

<NavBar/>
{@render children()}
<Footer/>

<svelte:boundary>
	<!--Component name-->

	{#snippet failed(error, reset)}
		<button onclick={reset}>oops! try again</button>
	{/snippet}
	<!--If it fails-->


	{#snippet pending()}
	<p>loading...</p>
	{/snippet}
	<!--If it loads-->

	<!--More on: https://svelte.dev/docs/svelte/svelte-boundary      -->
</svelte:boundary>

<svelte:head>
    <title></title>
	<meta name="description" content="Cheapest and best deals" />
</svelte:head>

