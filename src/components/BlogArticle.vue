<template>
	<div class="project-images col-12 d-flex justify-content-between pt-5 g-1">
		<div
			v-for="(article, index) in blog"
			:key="index"
			class="position-relative"
		>
			<img :src="article.image" alt="blog article" />
			<div class="article-box col-10" role="button">
				<article class="transition">
					<time>{{ article.date }}</time>
					<h6 class="py-3">{{ article.title }}</h6>
					<span>{{ article.text }}</span>
				</article>
			</div>
		</div>
	</div>
</template>
<script>
export default {
	name: "Article",
	data() {
		return {
			blog: [
				{
					image:
						require("@/assets/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg"),
					date: "july 4, 2019 | by paul",
					title: "Canadian Consulting Firm acquired by UK Giant",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a ...",
				},
				{
					image:
						require("@/assets/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg"),
					date: "july 4, 2019 | by paul",
					title: "Canadian Consulting Firm acquired by UK Giant",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a ...",
				},
			],
		};
	},
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_vars.scss";
.article-box {
	position: absolute;
	bottom: 0;
	right: 0;
}
article {
	background-color: $alfa_color;
	padding: 40px;
}
article:hover {
	background-color: $psi_color;
}
time {
	font-weight: 500;
	color: $gamma_color;
}
</style>