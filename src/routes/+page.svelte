<script>
	import Hero from '$lib/components/Hero.svelte';
	import Info from '$lib/components/Info.svelte';
	import Tjenester from '$lib/components/Tjenester.svelte';
</script>

<div class="hero-container">
	<Hero />
</div>
<main>
	<section id="info">
		<Info />
	</section>

	<section class="tjenester">
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
		width: 100%;
	}

	.tjenester {
		margin: 256px 0;
	}
</style>
