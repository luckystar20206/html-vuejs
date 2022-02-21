<template>
	<div id="app">
		<Header />
		<Main />
		<Footer />
	</div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
	name: "App",
	components: { Header, Main, Footer },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
*::-webkit-scrollbar {
	width: 8px;
	height: 8px;
}
*::-webkit-scrollbar-thumb {
	background-color: $psi_color;
	border: 3px solid $psi_color;
}
body {
	color: $alfa_color;
	font-family: $primary-font;
	background-color: $beta_color;
}
main {
	overflow: hidden;
}
</style>