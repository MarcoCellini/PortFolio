<script>
	import { page } from '$app/stores';
	import home from '$lib/images/home.png';
	import github from '$lib/images/github.svg';
</script>

<header>
	<div class="corner" id="home">
		<a href="/">
			<img src={home} alt="Logo-home" />
		</a>
	</div>

	<nav>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L1,2 C1.5,3 1.5,3 2,3 L2,0 Z" />
		</svg>
		<ul>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/ed-civica' ? 'page' : undefined}>
				<a href="/ed-civica">Educazione Civica</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/2020-2021') ? 'page' : undefined}>
				<a href="/2020-2021">2020-2021</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/2021-2022') ? 'page' : undefined}>
				<a href="/2021-2022">2021-2022</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/2022-2023') ? 'page' : undefined}>
				<a href="/2022-2023">2022-2023</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/2023-2024') ? 'page' : undefined}>
				<a href="/2023-2024">2023-2024</a>
			</li>
		</ul>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
		</svg>
	</nav>

	<div class="corner">
		<a href="https://github.com/MarcoCellini/PortFolio/tree/main/portfolio-ed-civica" target="_blank">
			<img src={github} alt="GitHub" />
		</a>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 3em;
		height: 3em;
		object-fit: contain;
	}

	nav {
		display: flex;
		justify-content: center;
		--background: #0925B3;
	}

	svg {
		width: 2em;
		height: 3em;
		display: block;
	}

	path {
		fill: var(--background);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li[aria-current='page']::before {
		--size: 10px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--color-theme-1);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 0.7rem;
		color: var(--color-text-2);
		font-weight: 700;
		font-size: 0.9rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--color-theme-1);
	}

	#home {
		margin: 0.1%;
	}
</style>
