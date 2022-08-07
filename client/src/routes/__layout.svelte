<script lang ts>
	import './layout.css';
	import '../styling/main.css';
	import Navbar from '../components/Navigation/NavbarComponent/001/Navbar.svelte';
</script>

<Navbar title="SvelteComponents" routes={['home', 'docs', 'about']} />

<slot />

<style>
</style>
