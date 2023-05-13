<script>
	import Divider from '$lib/components/Divider.svelte';
	import sidePattern from '$lib/assets/side-pattern.jpg';
	import Project from '$lib/components/Project.svelte';
</script>

<div class="container">
	<div class="title-container">
		<div class="pattern">
			<img src={sidePattern} alt="Topgrafi mønster" />
		</div>
		<div class="title">
			<h2>Utvalgte prosjekter</h2>
		</div>
	</div>
	<div class="projects">
		<div class="project">
			<Project />
		</div>
		<div class="project">
			<Project />
		</div>
		<div class="project">
			<Project />
		</div>
		<div class="project">
			<Divider />
		</div>
		<div class="project">
			<Project />
		</div>
		<div class="project">
			<Project />
		</div>
		<div class="project">
			<Project />
		</div>
	</div>
</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.title-container {
		display: flex;
		align-items: center;
		gap: 24px;
		margin-bottom: 64px;
	}

	.pattern {
		position: relative;
		width: 50%;
		z-index: -1;
		left: -256px;
	}

	.title {
		width: 50%;
	}

	.project {
		margin-bottom: 128px;
	}

	h2 {
		font-size: 93px;
	}
</style>
