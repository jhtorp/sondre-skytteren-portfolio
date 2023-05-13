<script>
	import BgPattern from '$lib/assets/bg-patter-jpg.jpg';
</script>

<div class="info-container">
	<div class="top-container">
		<div class="title-container">
			<h1>UX/UI</h1>
			<h1 class="h2-offset">designer</h1>
		</div>
		<div class="right-container">
			<img src={BgPattern} alt="" />
		</div>
	</div>
	<div class="bottom-container">
		<div class="air" />
		<p>
			UX design handler om å skape en best mulig brukeropplevelse når man interagerer med en
			løsning. Gjennom bruk av riktige metoder og verktøy innen design, er målet mitt å skape
			digitale løsninger som er brukervennlige og oppfyller behovene til brukerne.
		</p>
	</div>
</div>

<style>
	.info-container {
		display: flex;
		flex-direction: column;
	}

	.top-container {
		display: flex;
		align-items: center;
	}

	.title-container {
		display: inline-block;
		flex: 1;
	}

	.right-container {
		flex: 2;
	}

	.h2-offset {
		position: relative;
		left: 150px;
	}

	img {
		width: 100%;
		height: auto;
	}

	.bottom-container {
		display: flex;
	}

	.air {
		flex: 1;
	}

	p {
		margin-top: 56px;
		flex: 2;
	}
</style>
