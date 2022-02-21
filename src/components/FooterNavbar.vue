<template>
	<nav>
		<div class="container">
			<div class="row">
				<div
					id="footer-navbar"
					class="d-flex justify-content-between align-items-center"
				>
					<div class="logo">
						<img :src="whiteLogo" alt="logo" />
					</div>
					<div class="footer-nav">
						<ul class="list-unstyled d-flex mb-0">
							<li v-for="(link, index) in navbarlinks"
						:key="index"><a class="transition" :href="link.url">{{link.text.toUpperCase()}}</a></li>
						</ul>
					</div>
					<div class="social-icons">
						<i v-for="(contact, index) in contacts" :key="index" class="fa-brands" :class="contact.icon" role="button"></i>
					</div>
				</div>
			</div>
			<div class="row">
				<div
					class="
						col
						p-0
						rights
						d-flex
						justify-content-between
						align-items-center
					"
				>
					<div class="d-flex flex-column">
						<span>Terms of use</span>
						<span>Privacy Environmental Policy</span>
					</div>
					<span>Copyright © 2022 Phlox Consulting. All Rights Reserved. </span>
				</div>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: "FooterNavbar",
	data() {
		return {
			whiteLogo: require("@/assets/images/logotype-2-150x25.png"),
			navbarlinks: [
				{ url: "#", text: "home" },
				{ url: "#", text: "about" },
				{ url: "#", text: "projects" },
				{ url: "#", text: "services" },
				{ url: "#", text: "blog" },
				{ url: "#", text: "contact" },
			],
			contacts: [
				{ title: "instagram", icon: "fa-brands fa-instagram" },
				{ title: "linkedin", icon: "fa-brands fa-linkedin-in" },
				{ title: "facebook", icon: "fa-brands fa-facebook-f" },
				{ title: "twitter", icon: "fa-brands fa-twitter" },
			],
		};
	},
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#footer-navbar {
	color: $omega_color;
	height: 200px;
	border-bottom: 1px solid $omega_color;

	li,
	i {
		padding: 20px 0;
		margin: 0 15px;
		font-weight: 400;
	}
	li:hover a,
	i:hover {
		color: $gamma_color;
	}
	i {
		color: $alfa_color;
		font-size: 18px;
	}
}
.rights {
	height: 100px;
	font-size: 14px;
}
</style>