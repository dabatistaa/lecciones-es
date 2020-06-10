<script>
	import Header from './components/Header.svelte';
	import Main from './components/Main.svelte';
	import Leccion from './components/Leccion.svelte';
</script>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

<Header />
<Main>
	<Leccion />
</Main>