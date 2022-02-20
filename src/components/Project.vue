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
						<div class="filter-box"></div>
					</div>
					<div class="filter-container">
						<img
							src="../assets/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg"
							alt="sponsorship project"
						/>
						<div class="filter-box"></div>
					</div>
					<div class="filter-container">
						<img
							src="../assets/images/z1el4c4p-790x592.jpg"
							alt="consultant project"
						/>
						<div class="filter-box"></div>
					</div>
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
			<SlideProject />
		</div>
	</section>
</template>

<script>
import SlideProject from "@/components/SlideProject";
export default {
	name: "Project",
	components: { SlideProject },
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
		i {
			font-size: 18px;
			padding: 18px;
			background-color: $opacity;
		}
		a:hover {
			color: $white;
		}
		i:hover {
			background-color: $aqua;
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
			img {
				width: 420px;
				height: 300px;
			}
			.filter-box:hover {
				z-index: 1;
				background-color: $red-opacity;
			}
		}
		.cs-right-text {
			text-align: right;
		}
	}
}
</style>