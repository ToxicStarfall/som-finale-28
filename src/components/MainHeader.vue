<script setup>
</script>

<template>
	<header>
		<img alt="Vue logo" class="logo" src="../assets/logo.svg" width="80" height="80" />

		<div class="wrapper">
			<h2 class="green">Polar Operations Corporation<!-- Abandoned Polar Bear Breeding Facility --></h2>
			<h4>Personnel Access Page</h4>
		</div>

		<button>Authorize</button>
	</header>
</template>

<style scoped>
	header {
		line-height: 1.5;
		padding: 1rem 2rem;
		display: flex;
	}
	
	.logo {
		padding: 0 1rem;
		display: block;
		align-self: center;
		/* margin: 0 auto 2rem; */
	}
	
	.wrapper {
		width: 100%;
		display: flex;
		justify-content: center; align-content: center;
		flex-direction: column;
    	flex-wrap: wrap;
	}

	h2, h4 {
		width: auto;
		font-size: 40px;
		font-weight: 500;
		text-align: center;
	}
	h4 {
		font-size: 20px;
		font-weight: 500;
	}
</style>
