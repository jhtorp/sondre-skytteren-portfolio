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
		background: var(--grey);
	}

	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		max-width: 1260px;
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

	p,
	span,
	a {
		color: var(--font-primary);
		font-family: 'Nunito', sans-serif;
		font-size: 24px;
		font-weight: 400;
	}
</style>
