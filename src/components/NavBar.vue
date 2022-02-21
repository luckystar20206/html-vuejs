<template>
	<div class="col-12">
		<div id="navbar" class="d-flex justify-content-between align-items-center">
			<div class="logo">
				<img :src="redLogo" alt="logo" />
			</div>
			<div class="nav">
				<ul class="list-unstyled d-flex">
					<li
						v-for="(link, index) in navbarlinks"
						:key="index"
						:class="{ active: index == 0 }"
					>
						<a class="transition" :href="link.url">{{
							link.text.toUpperCase()
						}}</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "NavBar",
	data() {
		return {
			redLogo: require("@/assets/images/logotype.png"),
			navbarlinks: [
				{ url: "#", text: "home" },
				{ url: "#", text: "about" },
				{ url: "#", text: "projects" },
				{ url: "#", text: "services" },
				{ url: "#", text: "blog" },
				{ url: "#", text: "contact" },
			],
		};
	},
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#navbar {
	height: 80px;
	letter-spacing: 0.5px;

	li {
		padding: 20px 0;
		margin: 0 15px;
		border-top: 5px solid transparent;
		font-weight: 100;
	}
	li:hover {
		border-top: 5px solid $alfa_color;
	}
	li.active {
		border-top: 5px solid $alfa_color;
		font-weight: 600;
	}
	li:hover a {
		color: $alfa_color;
	}
}
</style>