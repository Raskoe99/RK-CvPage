<script>
	import Topbar from "../components/Topbar.svelte";
</script>

<Topbar/>
<main>
	<h1>Hello and welcome!</h1>
	<div class="bodyText">
        Oh no, this must look incredibly ugly
    </div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>