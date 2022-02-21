<template>
	<section id="about-us">
		<div class="container-fluid ps-0 ms-0 ">
			<div class="row ">
				<div class="col-4 offset-7">
					<div id="spotlight" class="d-flex flex-column justify-content-center px-5">
						<div class="spotlight-title">
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
				<div class="side-section">
					<div class="container h-100">
						<div class="row h-100 align-items-center">
							<div class="col-4 offset-1">
								<h4>WE HELP TO DELIVER THE BUSINESS CASE</h4>
							</div>
							<div class="col-5 offset-1">
								<p>
									When, while lovely valley teems with vapour around meand
									meridian sun strikes the upper impenetrable foliage of my
									trees, and but a thousand unknown
								</p>
								<a class="cs-button btn-transition" href="#" role="button"
									>GET STARTED</a
								>
							</div>
						</div>
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
	height: 800px;

	#spotlight {
		height: 800px;
	}
	.highlight {
		margin-bottom: 8px;
	}
	.side-section {
		height: 400px;
		width: 85%;
		background-color: $psi_color;
		position: relative;
		color: $beta_color;

		.cs-button {
			color: $alfa_color;
			background-color: $gamma_color;
			position: absolute;
			bottom: 0;
			right: 0;
		}
		.cs-button:hover {
			background-color: $beta_color;
		}
		p {
			color: $beta_color
		}
	}
}
</style>