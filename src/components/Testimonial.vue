<template>
	<div id="testimonial">
		<div class="col-12 d-flex flex-column">
			<h2 class="text-center">TESTIMONIAL</h2>
			<div class="col-7 d-flex flex-column align-items-end align-self-end pt-4">
				<div class="highlight"></div>
				<p class="cs-right-text">WHAT'S THE CUSTOMER SAY ABOUT OUR WORK</p>
			</div>
		</div>
		<div class="testimonial-reviews">
			<div class="row h-100">
				<div class="col-12 h-100 pe-5 d-flex">
					<div
						v-for="(testimonial, index) in testimonials"
						:key="index"
						class="testimonial-card position-relative col-4 h-100"
						role="button"
					>
						<img
							:src="testimonial.image"
							:alt="testimonial.author"
							class="h-100 w-100"
						/>
						<div
							class="
								testimonial-box
								d-flex
								flex-column
								justify-content-center
								h-100
								px-5
							"
						>
							<p class="pb-3">{{ testimonial.text }}</p>
							<h5>
								<strong>{{ testimonial.author }}</strong>
							</h5>
							<span>{{ testimonial.company }}</span>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "Testimonial",
	data() {
		return {
			testimonials: [
				{
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little .",
					author: " Vera Duncan",
					company: "Amazon Inc.",
					image: require("@/assets/images/oliver-ragfelt-488196-2.jpg"),
				},
				{
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little ",
					author: " Vera Duncan",
					company: "Amazon Inc.",
					image: require("@/assets/images/12679.jpg"),
				},
				{
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a thousand unknown plants are noticed by when I hear the buzz of the little ",
					author: " Vera Duncan",
					company: "Amazon Inc.",
					image: require("@/assets/images/oliver-ragfelt-488196-unsplash.jpg"),
				},
			],
		};
	},
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_vars.scss";
#testimonial {
	.cs-right-text {
		text-align: right;
		font-size: 44px;
	}
	.testimonial-reviews {
		height: 500px;
		width: 1600px;
		background-color: $alfa_color;
		color: $beta_color;

		.highlight {
			margin-right: 0;
		}
		.testimonial-box {
			position: absolute;
			bottom: 0;
			right: 0;
		}
		img {
			opacity: 0;
		}
		.testimonial-card:hover img {
			opacity:1;
			transition: opacity .5s ease-out;
		}
	}
}
</style>