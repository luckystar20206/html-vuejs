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
							<a class="view-all" href="#">VIEW ALL</a>
						</div>
					</div>
				</div>
				<div class="project-images col-12 d-flex justify-content-between pt-5 g-1">
					<div class="position-relative ">
						<img
							src="../assets/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg"
							alt="blog article"
						/>
						<div class="article-box col-10" role="button">
							<article>
								<time>july 4, 2019 | by paul</time>
								<h6 class="py-3">
									Canadian Consulting Firm acquired by UK Giant
								</h6>
								<span>
									When, while lovely valley teems with vapour around meand
									eridian sun strikes the upper impenetrable foliage of my
									trees, and but a ...
								</span>
							</article>
						</div>
					</div>
					<div class="position-relative">
						<img
							src="../assets/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg"
							alt="blog article"
						/>
						<div class="article-box col-10" role="button">
							<article>
								<time>july 4, 2019 | by paul</time>
								<h6 class="py-3">
									Canadian Consulting Firm acquired by UK Giant
								</h6>
								<span>
									When, while lovely valley teems with vapour around meand
									eridian sun strikes the upper impenetrable foliage of my
									trees, and but a ...
								</span>
							</article>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "Blog",
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
		color: $darkblue;
	}
	img {
		margin-bottom: 100px;
		width: 650px;
		height: auto;
	}
	.article-box {
		position: absolute;
		bottom: 0;
		right: 0;
	}
	article {
		background-color: $white;
		padding: 40px;
	}
	h6 {
		font-size: 30px;
		color: $black;
		font-family: $secondary-font;
	}
	span {
		color: $grey;
	}
	time {
		font-weight: 500;
		color: $red;
	}
}
</style>