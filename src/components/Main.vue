<template>
	<main>
		<Consultants />
		<section id="about-us"></section>
		<section id="projects"></section>
		<section id="blog"></section>
	</main>
</template>

<script>
import Consultants from "./Consultants.vue";

export default {
	name: "Main",
	components: { Consultants },
};
</script>

<style lang="scss" scoped>
</style>