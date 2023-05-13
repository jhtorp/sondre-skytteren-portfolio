<script>
	import '../global.css';
	import logo from '$lib/assets/logo-full.svg';
</script>

<div class="full-width nav-bg">
	<header>
		<div class="logo-container">
			<a href="/"><img src={logo} alt="Sondre Skytteren sin logo" /></a>
		</div>
		<nav>
			<ul>
				<li><a class="nav-link" href="/prosjekter">Prosjekter</a></li>
				<li><a class="nav-link" href="/">sondresky@gmail.com</a></li>
			</ul>
		</nav>
	</header>
</div>
<slot />

<style>
	.full-width {
		width: 100%;
	}

	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		max-width: 1400px;
		margin: 0 auto;
		min-height: 8vh;
	}
	nav > ul {
		display: flex;
		gap: 32px;
	}

	a,
	li {
		all: unset;
	}

	a {
		cursor: pointer;
	}

	.nav-link {
		font-size: 17px;
	}

	/* Global generic styles */
	:global(html) {
		scroll-behavior: smooth;
	}

	:global(h1, h2, h3, h4) {
		font-family: 'agrandir', sans-serif;
		color: var(--font-primary);
	}

	:global(h1) {
		font-size: 93px;
	}
	:global(h2) {
		font-size: 60px;
	}

	:global(p, a, ul, li, span, button:not(h1, h2)) {
		font-family: 'Nunito', sans-serif;
		color: var(--font-primary);
	}

	:global(p) {
		font-size: 24px;
		line-height: 150%;
	}
	:global(.text-sm) {
		font-size: 20px;
	}

	:global(button) {
		font-size: 21px;
		font-weight: 600;
		border: 1px solid var(--font-primary);
		padding: 12px 24px;
		border-radius: 10px;
		cursor: pointer;
		background: none;
	}
</style>
