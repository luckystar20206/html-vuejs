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
	color: $white;
	padding-top: 250px;
	background-color: $darkblue;
	h2 {
		letter-spacing: 3px;
		font-size: 16px;
	}
	p {
		font-family: $secondary-font;
		font-size: 44px;
		font-weight: 700;
		line-height: 60px;
	}
	.highlight {
		margin: 0 15px 5px 0;
		width: 50px;
		border-bottom: 2px solid $aqua;
	}
	a {
		padding: 25px 50px;
		background-color: $aqua;
		color: $black;
		letter-spacing: 3px;
	}
	a.view-all:hover {
		color: $white;
		background-color: $red;
	}
}
</style>