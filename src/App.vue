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
	data() {
		return {
			phloxConsulting: {
				whiteLogo: "../assets/images/logotype.png",
				redLogo: "../assets/images/logotype-2-150x25.png",
				navbar: [
					{ url: "#", text: "home" },
					{ url: "#", text: "about" },
					{ url: "#", text: "projects" },
					{ url: "#", text: "services" },
					{ url: "#", text: "blog" },
					{ url: "#", text: "contact" },
				],
				consulting: [
					{
						url: "#",
						title: "statistical consulting",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
						icon: "fa-solid fa-chart-column",
					},
					{
						url: "#",
						title: "banking consulting",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
						icon: "fa-solid fa-wallet",
					},
					{
						url: "#",
						title: "digital consulting",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
						icon: "fa-solid fa-bullhorn",
					},
					{
						url: "#",
						title: "enterprise consulting",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
						icon: "fa-solid fa-minimize",
					},
				],
				project: [
					{ img: "../assets/images/DRY-1-790x592.jpg", alt: "project dry" },
					{
						img: "../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg",
						alt: "sponsorship proposal",
					},
					{
						img: "../assets/images/z1el4c4p-790x592.jpg",
						alt: "consulting vizeon",
					},
				],
				testimonial: [
					{
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little .",
						author: " Vera Duncan",
						company: "Amazon Inc.",
					},
					{
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little ",
						author: " Vera Duncan",
						company: "Amazon Inc.",
					},
					{
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little ",
						author: " Vera Duncan",
						company: "Amazon Inc.",
					},
				],
				blog: [
					{
						image:
							"../assets/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg",
						date: "july 4, 2019 | by paul",
						title: "Canadian Consulting Firm acquired by UK Giant",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a ...",
					},
					{
						image:
							"../assets/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg",
						date: "july 4, 2019 | by paul",
						title: "Canadian Consulting Firm acquired by UK Giant",
						text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a ...",
					},
				],
				contacts: [
					{ title: "instagram", icon: "fa-brands fa-instagram" },
					{ title: "linkedin", icon: "fa-brands fa-linkedin-in" },
					{ title: "facebook", icon: "fa-brands fa-facebook-f" },
					{ title: "twitter", icon: "fa-brands fa-twitter" },
				],
			},
		};
	},
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
