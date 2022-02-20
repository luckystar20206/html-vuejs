<template>
	<section id="project">
		<div class="container">
			<div class="row main-project">
				<div class="col-12 pb-5">
					<div class="d-flex align-items-center">
						<div class="highlight mb-2 me-2"></div>
						<h2>PROJECT</h2>
					</div>
					<div class="d-flex justify-content-between align-items-center">
						<p class="pt-3 col-8">
							OUR EXPERT TRUSTED CONSULTANTS HELP CLIENTS
						</p>
						<div>
							<a href="#"><i class="fa-solid fa-arrow-left-long" role="button"></i></a>
							<a href="#"><i class="fa-solid fa-arrow-right-long" role="button"></i></a>
						</div>
					</div>
				</div>
				<div class="project-images col-12 d-flex justify-content-between g-1">
					<img src="../assets/images/DRY-1-790x592.jpg" alt="dry project" />
					<img
						src="../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg"
						alt="sponsorship project"
					/>
					<img
						src="../assets/images/z1el4c4p-790x592.jpg"
						alt="consultant project"
					/>
				</div>
				<div class="col-12 d-flex flex-column">
					<h2 class="text-center">TESTIMONIAL</h2>
					<div
						class="col-7 d-flex flex-column align-items-end align-self-end pt-4"
					>
						<div class="highlight"></div>
						<p class="cs-right-text">WHAT'S THE CUSTOMER SAY ABOUT OUR WORK</p>
					</div>
				</div>
			</div>
			<div class="slide-in">
				<div class="container h-100">
					<div class="row h-100">
						<div
							class="col-12 d-flex align-items-center justify-content-between"
						>
							<div class="col-4 pe-4">
								<p class="pb-3">
									When, while lovely valley teems with vapour around meand
									eridian sun strikes the upper impenetrable foliage of my
									trees, and but a thousand unknown plants are noticed by when I
									hear the buzz of the little .
								</p>
								<h5><strong>Vera Duncan</strong></h5>
								<span>Amazon Inc.</span>
							</div>
							<div class="col-4 pe-4">
								<p class="pb-3">
									When, while lovely valley teems with vapour around meand
									eridian sun strikes the upper impenetrable foliage of my
									trees, and but a thousand unknown plants are noticed by when I
									hear the buzz of the little .
								</p>
								<h5><strong>Vera Duncan</strong></h5>
								<span>Amazon Inc.</span>
							</div>
							<div class="col-4 pe-4">
								<p class="pb-3">
									When, while lovely valley teems with vapour around meand
									eridian sun strikes the upper impenetrable foliage of my
									trees, and but a thousand unknown plants are noticed by when I
									hear the buzz of the little .
								</p>
								<h5><strong>Vera Duncan</strong></h5>
								<span>Amazon Inc.</span>
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
	name: "Project",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#project {
	color: $white;
	padding-top: 350px;
	background-color: $darkblue;
	
	.main-project {
		.highlight {
			width: 50px;
			border-bottom: 2px solid $aqua;
		}
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
		.fa-arrow-left-long {
			margin-right: 20px;
		}
		a:hover {
			color: $red;
		}
		i {
			font-size: 18px;
			padding: 18px;
			background-color: $opacity;
		}
		.project-images {
			padding-bottom: 100px;
			img {
				width: 420px;
				height: 300px;
			}
		}
		.cs-right-text {
			text-align: right;
		}
	}
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
		span,p {
			color: $grey;
		}
	}
}
</style>