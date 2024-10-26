<script>
	import '../app.css';
	import { Header, Footer, } from '$widgets';



	const { children } = $props();
</script>

<Header />

<main class="overflow-hidden">
	{@render children()}
</main>

<Footer />



<style lang="postcss">

</style>



