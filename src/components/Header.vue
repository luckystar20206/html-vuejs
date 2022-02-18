<template>
	<header>
		<div class="container">
			<div class="row">
				<NavBar />
				<Spotlight />
			</div>
		</div>
	</header>
</template>

<script>
import NavBar from "./NavBar.vue";
import Spotlight from "./Spotlight.vue";
export default {
	name: "Header",
	components: {NavBar, Spotlight}
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
header {
	background-image: url("../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
	background-repeat: no-repeat;
	background-position: top right;
	background-color: $bg-darkblue;

	height: 1000px;
	color: $text-white;
}
</style>