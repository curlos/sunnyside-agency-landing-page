<script>
	import Navbar from "./components/Navbar.svelte";
	export let name;
</script>

<main>
	<div class="headerContainer">
		<Navbar />
		<div class="header">WE ARE CREATIVES</div>
	</div>
</main>

<style>
	@import url("https://fonts.googleapis.com/css2?family=Barlow:wght@600&family=Fraunces:wght@700;900&display=swap");

	main {
		font-family: Barlow;
		font-size: 18px;
		font-weight: 600px;
	}

	.headerContainer {
		display: flex;
		flex-direction: column;
		height: 100vh;
	}

	.header {
		background-image: url("/assets/images/desktop/image-header.jpg");
		background-size: cover;
		background-position: center;
		flex: 1;
		color: #ffffff;
		text-align: center;
		font-family: Fraunces;
		color: #ffffff;
		font-size: 56px;
		letter-spacing: 8.75px;
		padding-top: 70px;
	}
</style>
