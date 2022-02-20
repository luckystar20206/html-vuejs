<template>
	<header>
		<div class="container">
			<div class="row">
				<NavBar />
				<Spotlight />
			</div>
		</div>
		<div class="fixed-icons">
			<a href="#"
				><i
					v-show="scY > 300"
					@click="toTop"
					class="fa-solid fa-arrow-up btn-transition"
					role="button"
				></i
			></a>
			<a href="#"><i class="fa-regular fa-comment" role="button"></i></a>
		</div>
	</header>
</template>

<script>
import NavBar from "./NavBar.vue";
import Spotlight from "./Spotlight.vue";
export default {
	name: "Header",
	components: { NavBar, Spotlight },
	data() {
		return {
			scTimer: 0,
			scY: 0,
		};
	},
	methods: {
		handleScroll: function () {
			if (this.scTimer) return;
			this.scTimer = setTimeout(() => {
				this.scY = window.scrollY;
				clearTimeout(this.scTimer);
				this.scTimer = 0;
			}, 100);
		},
		toTop: function () {
			window.scrollTo({
				top: 0,
				behavior: "smooth",
			});
		},
	},
	mounted() {
		window.addEventListener("scroll", this.handleScroll);
	},
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
header {
	background-image: url("../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
	background-repeat: no-repeat;
	background-position: top right;
	background-color: $darkblue;

	height: 1000px;
	color: $white;

	.fixed-icons {
		position: fixed;
		bottom: 0;
		right: 0;
		margin-bottom: 40px;
	}
	a + a {
		margin: 0 50px 0 20px;
	}
	.fa-comment {
		font-size: 30px;
		padding: 16px;
		border-radius: 50%;
		background-color: $lilac;
	}
	.fa-comment:hover {
		color: $white;
	}

	.fa-arrow-up {
		font-size: 14px;
		padding: 12px 15px;
		border-radius: 50%;
		color: $black;
		background-color: $white;
		border: 1px solid $black;
	}
	.fa-arrow-up:hover {
		color: $white;
		background-color: $black;
	}
}
</style>