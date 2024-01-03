<script>
	import { page } from '$app/stores';
	import github from '$lib/images/github.svg';
</script>

<header>
	<div class="corner" id="home" />

	<nav>
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
	</nav>

	<div class="corner">
		<a
			href="https://github.com/MarcoCellini/PortFolio/tree/main/portfolio-ed-civica"
			target="_blank"
			rel="noreferrer"
		>
			<img src={github} alt="GitHub" />
		</a>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		position: fixed;
		width: 100%;
		background-color: rgb(97, 236, 211, 0.96);
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
		--background: #0925b3;
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
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li[aria-current='page']::before {
		--size: 10px; /* Set the size of the line */
		content: '';
		width: 50%; /* Set the width of the line */
		height: 5px; /* Set the height of the line */
		position: absolute;
		left: calc(30% - (var(--size) / 2)); /* Position the line horizontally in the center */
		background-color: var(--color-theme-1); /* Set the color of the line */
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

	li a {
		color: #0925b3;
		font-size: 1rem;
	}

	li[aria-current='page'] a {
		color: var(--color-theme-1);
	}
</style>
