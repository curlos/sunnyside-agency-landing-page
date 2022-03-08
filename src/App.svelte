<script>
	import Navbar from "./components/Navbar.svelte";
	export let name;
</script>

<main>
	<Navbar />
</main>

<style>
	@import url("https://fonts.googleapis.com/css2?family=Barlow:wght@600&family=Fraunces:wght@700;900&display=swap");

	main {
		font-family: Barlow;
		font-size: 18px;
		font-weight: 600px;
	}
</style>
