<script lang ts>
	import Navbar from '../../components/Navigation/NavbarComponent/001/Navbar.svelte';
	import './docs.css';
</script>

<svelte:head>
	<title>Docs</title>
</svelte:head>
<div class="container">
	<section id="intro">
		<ul>
			<li>
				<a href="#components">Components</a>
			</li>
			<li>
				<a href="#styling">Styling</a>
			</li>
		</ul>
	</section>

	<section id="components">
		<h1>Components</h1>
		<hr />
		<h2>Navigation</h2>
		<h3>001</h3>
		<Navbar title={'title'} routes={['Route 1', 'Route 2']} />
	</section>
	<section id="styling">
		<h1>Styling</h1>
		<hr />
		<h2>Container</h2>
		<p>The container class reduces the width to 80%, while centering the div</p>
		<section id="code">
			<h1>Code</h1>
		</section>
	</section>
</div>

<style>
</style>
