<script>
	import Hero from '$lib/components/Hero.svelte';
	import Info from '$lib/components/Info.svelte';
	import Tjenester from '$lib/components/Tjenester.svelte';
</script>

<div class="hero-container">
	<Hero />
</div>
<main>
	<section>
		<Info />
	</section>

	<section>
		<Tjenester />
	</section>
</main>

<style>
	main {
		display: flex;
		align-items: center;
		flex-direction: column;
	}

	section {
		max-width: 1260px;
		margin: 128px 0;
		width: 100%;
	}
</style>
