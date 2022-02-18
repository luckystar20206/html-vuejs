<template>
	<main>
		<Consultants />
		<AboutUs />
		<Project />
		<Blog />
	</main>
</template>

<script>
import Consultants from "./Consultants.vue";
import AboutUs from "./AboutUs.vue";
import Project from "./Project.vue";
import Blog from "./Blog.vue";

export default {
	name: "Main",
	components: { Consultants, AboutUs, Project, Blog },
};
</script>

<style lang="scss" scoped>
</style>