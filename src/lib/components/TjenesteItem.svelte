<script>
	export let src;
	export let title;
	export let text;
</script>

<div class="container">
	<div class="wrapper">
		<div class="img-container">
			<img {src} alt="ikon" />
		</div>
		<p>{title}</p>
		<p class="text-sm">
			{text}
		</p>
	</div>
</div>

<style>
	.img-container {
		margin-top: 88px;
		margin-bottom: 24px;
	}

	.container {
		height: 400px;
		display: flex;
		border-bottom: 1px solid #070e2876;
	}

	p:not(.text-sm) {
		font-weight: bold;
		margin-bottom: 8px;
	}
</style>
