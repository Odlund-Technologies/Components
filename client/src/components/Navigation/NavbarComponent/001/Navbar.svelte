<script>
	import './Navbar.css';
	export let routes = ['home', 'about'];
	export /**
	 * @type {String}
	 */
	let title;
</script>

<nav>
	<div class="left">
		<a href="/">
			<h1>{title.toUpperCase()}</h1>
		</a>
	</div>
	<div class="wrapper">
		<div class="center">
			<ul>
				{#each routes as route}
					<li><a href={route.toLowerCase()}>{route}</a></li>
				{/each}
			</ul>
		</div>
		<div class="right">
			<button>Get started <span /></button>
		</div>
	</div>
</nav>
