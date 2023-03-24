<script>
	import {base} from "$app/paths";
</script>

<header>
	<h1>Majed Naser Personal Website</h1>
	<nav>
		<a href="{base}/">Portfolio</a>
		<a href="{base}/about">About</a>
		<a href="{base}/experience">Experience</a>
		<a href="{base}/education">Education</a>
		<a href="{base}/projects">Projects</a>
		<a href="{base}/comic">Comic</a>
	</nav>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}
	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 0.5rem;
		color: var(--color-text);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--color-theme-1);
	}
</style>
