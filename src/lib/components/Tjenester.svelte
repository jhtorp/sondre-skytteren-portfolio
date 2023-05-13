<script>
	import Divider from '$lib/components/Divider.svelte';
	import TjenesteItem from '$lib/components/TjenesteItem.svelte';
	import IconEdit from '$lib/assets/icon-edit.svg';
	import IconResponsive from '$lib/assets/icon-responsive.svg';
	import IconGlobe from '$lib/assets/icon-globe.svg';
	import IconBox from '$lib/assets/icon-box.svg';
</script>

<div class="tjenester-container">
	<div class="title-container">
		<h2>Hva jeg gjør</h2>
	</div>
	<div class="tjeneste-container">
		<div class="tjeneste-row">
			<div class="tjeneste-item">
				<TjenesteItem
					src={IconEdit}
					title="Grafisk Design"
					text="Jeg har mange års erfaring som grafisk designer, og kan bidra med design av visuell profil eller trykksaker."
				/>
			</div>
			<div class="tjeneste-item">
				<TjenesteItem
					src={IconResponsive}
					title="Interaksjondesign"
					text="Optimal brukervennlighet er nøkkelen til et godt design. Et grundig utført UX og UI-design bidrar til å forebygge frustrasjon hos brukeren."
				/>
			</div>
		</div>
		<div class="tjeneste-row">
			<div class="tjeneste-item">
				<TjenesteItem
					src={IconBox}
					title="Digital strategi"
					text="Jeg tilbyr rådgivningstjenester for å hjelpe bedrifter med å forbedre digital synlighet."
				/>
			</div>
			<div class="tjeneste-item">
				<TjenesteItem
					src={IconGlobe}
					title="Analyse og optimalisering"
					text="Jeg analyserer og optimaliserer eksisterende digitale løsninger for å forbedre brukeropplevelsen"
				/>
			</div>
		</div>
	</div>
</div>

<style>
	.tjenester-container {
		width: 100%;
	}

	.tjeneste-container {
		display: flex;
		flex-direction: column;
	}

	.tjeneste-row {
		display: flex;
		gap: 24px;
	}

	.tjeneste-item {
		flex: 1;
	}

	.title-container {
		width: 100%;
	}
</style>
