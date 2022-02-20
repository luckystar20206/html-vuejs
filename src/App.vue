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
}

*::-webkit-scrollbar-track {
	background: $darkblue;
}

*::-webkit-scrollbar-thumb {
	background-color: $aqua;
	border: 3px solid $aqua;
}
body {
	font-family: $primary-font;
}
main {
	overflow: hidden;
}
</style>
