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
						class="
							testimonial-left
							img-transition
							col-4
							px-5
							h-100
							d-flex
							flex-column
							justify-content-center
						"
						role="button"
					>
						<p class="pb-3">
							When, while lovely valley teems with vapour around meand eridian
							sun strikes the upper impenetrable foliage of my trees, and but a
							thousand unknown plants are noticed by when I hear the buzz of the
							little .
						</p>
						<h5><strong>Vera Duncan</strong></h5>
						<span>Amazon Inc.</span>
					</div>
					<div
						class="
							testimonial-middle
							img-transition
							col-4
							px-5
							h-100
							d-flex
							flex-column
							justify-content-center
						"
						role="button"
					>
						<p class="pb-3">
							When, while lovely valley teems with vapour around meand eridian
							sun strikes the upper impenetrable foliage of my trees, and but a
							thousand unknown plants are noticed by when I hear the buzz of the
							little .
						</p>
						<h5><strong>Vera Duncan</strong></h5>
						<span>Amazon Inc.</span>
					</div>
					<div
						class="
							testimonial-right
							img-transition
							col-4
							px-5
							h-100
							d-flex
							flex-column
							justify-content-center
						"
						role="button"
					>
						<p class="pb-3">
							When, while lovely valley teems with vapour around meand eridian
							sun strikes the upper impenetrable foliage of my trees, and but a
							thousand unknown plants are noticed by when I hear the buzz of the
							little .
						</p>
						<h5><strong>Vera Duncan</strong></h5>
						<span>Amazon Inc.</span>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "Testimonial",
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
		.testimonial-left:hover {
			background-image: url("../assets/images/oliver-ragfelt-488196-unsplash.jpg");
		}
		.testimonial-middle:hover {
			background-image: url("../assets/images/oliver-ragfelt-488196-2.jpg");
		}
		.testimonial-right:hover {
			background-image: url("../assets/images/12679.jpg");
		}
		.testimonial-left:hover,
		.testimonial-middle:hover,
		.testimonial-right:hover {
			background-repeat: no-repeat;
			background-size: cover;
		}
	}
}
</style>