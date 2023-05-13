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
		margin-bottom: 24px;
	}

	.container {
		height: 300px;
		display: flex;
		align-items: center;
		border-bottom: 1px solid #dcdcdc;
	}

	p:not(.text-sm) {
		font-weight: bold;
		margin-bottom: 8px;
	}
</style>
