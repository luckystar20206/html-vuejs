<template>
	<footer>
		<FooterSpotlight />
		<FooterNavbar />
	</footer>
</template>

<script>
import FooterSpotlight from "@/components/FooterSpotlight";
import FooterNavbar from "@/components/FooterNavbar";
export default {
	name: "Footer",
	components: { FooterSpotlight, FooterNavbar },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
</style>