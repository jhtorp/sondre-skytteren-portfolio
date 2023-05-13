<script>
	import ProjectImg from '$lib/assets/project-placeholder.jpg';
</script>

<div class="container">
	<div class="left"><img src={ProjectImg} alt="Mockup" /></div>
	<div class="right">
		<span class="tag">WEBDESIGN / UX DESIGN</span>
		<div class="mid">
			<h3 class="title">Composure Skin Clinic</h3>
			<span class="sub-title">Webdesign</span>
			<p class="text-sm">
				Composure Skin Clinic er en medisinsk klinikk innen kosmetisk hudpleie, dermatologi og
				injeksjoner. Jeg designet en nettside for å styrke virksomhetens identitet på nett.
			</p>
		</div>
		<div class="btn-container">
			<button><a href="/prosjekter/[slug]">Sjekk ut</a></button>
		</div>
	</div>
</div>

<style>
	.container {
		display: flex;
		max-width: 1260px;
	}

	.right {
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		padding-inline: 64px;
	}

	.tag {
		font-size: 11px;
	}

	.title {
		font-size: 24px;
		font-weight: 300;
	}

	.sub-title {
		font-size: 18px;
		font-weight: bold;
	}

	p {
		margin-top: 24px;
	}

	button {
		border-radius: 0;
		border: none;
		background: #444444;
		color: white;
	}

	a {
		all: unset;
	}
</style>
