<script>
	import Hero from '$lib/components/Hero.svelte';
	import Info from '$lib/components/Info.svelte';
	import Tjenester from '$lib/components/Tjenester.svelte';
	import Projects from '$lib/components/Projects.svelte';
	import Contact from '$lib/components/Contact.svelte';
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
	<section class="projects">
		<Projects />
	</section>
	<section class="contact">
		<Contact />
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
		margin: 256px 0 0 0;
	}
	.projects {
		display: flex;
		justify-content: center;
		margin: 128px 0;
	}

	.contact {
		margin-bottom: 128px;
	}
</style>
