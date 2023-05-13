<script>
	import Divider from '$lib/components/Divider.svelte';
	import arrow from '$lib/assets/arrow-down.svg';
</script>

<div class="container">
	<div class="divider"><Divider /></div>
	<div class="contact">
		<h2>Jeg tar gjerne en prat med deg!</h2>
		<button class="slide">
			<a href="#">
				<p>Trykk her for en uforpliktende prat!</p>
				<img src={arrow} alt="pil" />
			</a>
		</button>
	</div>
</div>

<style>
	.divider {
		margin-bottom: 64px;
	}

	.contact {
		display: flex;
	}

	a {
		all: unset;
		display: flex;
	}

	img {
		transform: rotate(-90deg);
	}
</style>
