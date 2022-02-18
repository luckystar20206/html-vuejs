<template>
	<main>
		<Consultants />
		<AboutUs />
		<section id="projects"></section>
		<section id="blog"></section>
	</main>
</template>

<script>
import Consultants from "./Consultants.vue";
import AboutUs from "./AboutUs.vue";

export default {
	name: "Main",
	components: { Consultants, AboutUs },
};
</script>

<style lang="scss" scoped>
</style>