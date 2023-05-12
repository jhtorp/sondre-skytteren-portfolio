<script>
	import sondre from '$lib/assets/sondre.jpg';
	import pattern from '$lib/assets/pattern.svg';
	import ArrowDown from '$lib/assets/arrow-down.svg';
	import Icon from '@iconify/svelte';
</script>

<div class="hero-main">
	<div class="full-width-container">
		<div class="hero-container">
			<div class="left">
				<h1 class="h1">La meg inspirere deg!</h1>
				<p>
					Gjennom bruk av riktige metoder og verktøy innen design, er mitt mål å skape digitale
					løsninger som er brukervennlige og oppfyller behovene til brukerne.
				</p>
				<div class="btn-container">
					<button>Kontakt meg</button>
				</div>
			</div>
			<div class="right">
				<img class="hero-img" src={sondre} alt="Bilde av Sondre Skytteren" />
			</div>
			<img class="pattern" src={pattern} alt="Mønster i bakgrunnen" />
		</div>
	</div>
	<div class="socials-container">
		<a href="https://www.linkedin.com/in/sondre-skytteren"
			><Icon icon="brandico:linkedin-rect" color="#b5b5b5;" width="40" height="40" /></a
		>
	</div>
	<div class="arrow-down-container">
		<a href="/"><img class="arrow-down" src={ArrowDown} alt="pil ned ikon" /></a>
	</div>
</div>

<style>
	p {
		width: 85%;
		line-height: 150%;
	}

	.hero-main {
		height: 92vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		gap: 24px;
		align-items: center;
	}

	.full-width-container {
		width: 100%;
		position: relative;
		display: flex;
		justify-content: center;
	}

	.pattern {
		position: absolute;
		right: 0;
		width: 50%;
		height: 100%;
		object-fit: cover;
		z-index: -1;
	}

	.hero-container {
		display: flex;
		justify-content: space-between;
		max-width: 1260px;
	}

	.hero-img {
		z-index: 1;
		height: 100%;
	}

	.left {
		flex: 1;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}
	.right {
		flex: 1;
		display: flex;
		justify-content: end;
	}

	.socials-container {
		width: 1260px;
		display: flex;
		justify-content: end;
	}

	.arrow-down-container {
		width: 100%;
		display: flex;
		justify-content: center;
	}

	.arrow-down {
		cursor: pointer;
	}
</style>
