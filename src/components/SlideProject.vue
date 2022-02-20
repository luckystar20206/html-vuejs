<template>
	<div class="slide-in">
		<div class="row h-100">
			<div class="col-12 h-100 pe-5 d-flex">
				<div class="testimonial-left img-transition col-4 px-5 h-100 d-flex flex-column justify-content-center" role="button">
					<p class="pb-3">
						When, while lovely valley teems with vapour around meand eridian sun
						strikes the upper impenetrable foliage of my trees, and but a
						thousand unknown plants are noticed by when I hear the buzz of the
						little .
					</p>
					<h5><strong>Vera Duncan</strong></h5>
					<span>Amazon Inc.</span>
				</div>
				<div class="testimonial-middle img-transition col-4 px-5 h-100 d-flex flex-column justify-content-center" role="button">
					<p class="pb-3">
						When, while lovely valley teems with vapour around meand eridian sun
						strikes the upper impenetrable foliage of my trees, and but a
						thousand unknown plants are noticed by when I hear the buzz of the
						little .
					</p>
					<h5><strong>Vera Duncan</strong></h5>
					<span>Amazon Inc.</span>
				</div>
				<div class="testimonial-right img-transition col-4 px-5 h-100 d-flex flex-column justify-content-center" role="button">
					<p class="pb-3">
						When, while lovely valley teems with vapour around meand eridian sun
						strikes the upper impenetrable foliage of my trees, and but a
						thousand unknown plants are noticed by when I hear the buzz of the
						little .
					</p>
					<h5><strong>Vera Duncan</strong></h5>
					<span>Amazon Inc.</span>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "SlideProject",
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_vars.scss";
.slide-in {
	height: 400px;
	width: 1600px;
	background-color: $white;
	color: $darkblue;

	h5 {
		font-size: 26px;
		letter-spacing: -2px;
		font-family: $secondary-font;
	}
	span,
	p {
		color: $grey;
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
}
</style>