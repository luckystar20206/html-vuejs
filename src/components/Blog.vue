<template>
	<section id="blog">
		<div class="container">
			<div class="row">
				<div class="col">
					<div class="d-flex align-items-center">
						<div class="highlight"></div>
						<h2>BLOG</h2>
					</div>
					<div class="d-flex justify-content-between align-items-center">
						<p class="pt-3 col-8">THE RECENT NEWS YOU MUST READ IT</p>
						<div>
							<a class="view-all btn-transition" href="#">VIEW ALL</a>
						</div>
					</div>
				</div>
				<BlogArticle />
			</div>
		</div>
	</section>
</template>

<script>
import BlogArticle from "@/components/BlogArticle";
export default {
	name: "Blog",
	components: { BlogArticle },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#blog {
	padding-top: 250px;

	a {
		padding: 25px 50px;
		background-color: $psi_color;
		color: $black;
	}
	a:hover {
		color: $alfa_color;
		background-color: $gamma_color;
	}
}
</style>