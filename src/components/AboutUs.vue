<template>
	<section id="about-us">
		<div class="container">
			<div class="row">
				<div class="col-5 offset-8">
					<div id="spotlight">
						<div class="d-flex align-items-center">
							<div class="highlight"></div>
							<h2>ABOUT US</h2>
						</div>
						<p class="pt-3">WE MAKE YOUR STRATEGY WORK</p>
						<span>
							When, while lovely valley teems with vapour around meand eridian
							sun strikes the upper impenetrable foliage of my trees, and but a
							thousand unknown plants are noticed when I hear the buzz of the
							little world among the stalks,and grow familiar indescribable
							forms of the insects .and flies, then I feel the presence of the
							Almighty .
						</span>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "AboutUs",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#about-us {
	background-image: url("../assets/images/business-people-working-together-on-project-and-5FHSKBL.jpg");
	background-repeat: no-repeat;
	background-position: top left;
	background-color: $darkblue;
	height: 800px;
	color: $white;
	#spotlight {
		padding: 240px 0 50px 0;
		h2 {
			letter-spacing: 3px;
			font-size: 16px;
		}
		p {
			font-family: $secondary-font;
			font-size: 60px;
			font-weight: 700;
			line-height: 60px;
		}
		span {
			color: $grey;
		}
		.highlight {
			margin: 0 15px 5px 0;
			width: 50px;
			border-bottom: 2px solid $aqua;
		}
	}
}
</style>