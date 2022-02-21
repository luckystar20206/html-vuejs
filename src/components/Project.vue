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
							<a href="#"
								><i
									class="fa-solid fa-arrow-left-long btn-transition"
									role="button"
								></i
							></a>
							<a href="#"
								><i
									class="fa-solid fa-arrow-right-long btn-transition"
									role="button"
								></i
							></a>
						</div>
					</div>
				</div>
				<div class="project-images col-12 d-flex justify-content-between g-1">
					<div class="filter-container">
						<img src="../assets/images/DRY-1-790x592.jpg" alt="dry project" />
						<div class="filter-box btn-transition"></div>
					</div>
					<div class="filter-container">
						<img
							src="../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg"
							alt="sponsorship project"
						/>
						<div class="filter-box btn-transition"></div>
					</div>
					<div class="filter-container">
						<img
							src="../assets/images/z1el4c4p-790x592.jpg"
							alt="consultant project"
						/>
						<div class="filter-box btn-transition"></div>
					</div>
				</div>
			</div>
			<Testimonial />
		</div>
	</section>
</template>

<script>
import Testimonial from "@/components/Testimonial";
export default {
	name: "Project",
	components: { Testimonial },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#project {
	padding-top: 550px;

	.main-project {
		i {
			font-size: 18px;
			padding: 18px;
			background-color: $opacity;
		}
		a:hover {
			color: $alfa_color;
		}
		i:hover {
			background-color: $psi_color;
		}
	}
	.project-images {
		padding-bottom: 100px;

		.filter-container {
			position: relative;
			cursor: pointer;
		}
		.filter-box {
			height: 300px;
			width: 420px;
			position: absolute;
			top: 0;
			left: 0;
		}
		.filter-box:hover {
			background-color: $red-opacity;
		}
	}
}
</style>