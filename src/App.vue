<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import MainHeader from './components/MainHeader.vue';
</script>

<template>
	<!-- <header>
		<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

		<div class="wrapper">
			<HelloWorld msg="You did it!"/>
		</div>
	</header> -->

	<MainHeader />

	<hr>

	<main>
		<!-- <TheWelcome/> -->
		Request Authorization ->
		Authorize Existing User ->

		<hr>
		Authorization Logs
		- - -
	</main>
</template>

<style scoped>
header {
	line-height: 1.5;
	display: flex;
}

.logo {
	display: block;
	width: 100px; height: 100px;
	/* margin: 0 auto 2rem; */
}

hr {
	width: 100%;
    height: 2px;
    border: none;
    background-image: linear-gradient(90deg, transparent, 40%, #ffffff, 60%, transparent);
}

main {
	padding: 2rem 4rem;
}
/* @media (min-width: 1024px) {
	header {
		display: flex;
		place-items: center;
		padding-right: calc(var(--section-gap) / 2);
	}

	.logo {
		margin: 0 2rem 0 0;
	}

	header .wrapper {
		display: flex;
		place-items: flex-start;
		flex-wrap: wrap;
	}
} */
</style>
