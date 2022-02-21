<template>
	<section id="consultants">
		<div class="d-flex">
			<h3>OUR CONSULTANTS CAN HELP YOU</h3>
			<div class="highlight"></div>
		</div>
		<div class="container">
			<div class="row">
				<div class="consults col-12 d-flex flex-wrap">
					<div class="statistical col-6 d-flex flex-row">
						<div>
							<i class="fa-solid fa-chart-column" role="button"></i>
						</div>
						<div>
							<h4 class="ps-5">STATISTICAL CONSULTING</h4>
							<p class="px-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
					<div class="digital col-6 d-flex flex-row">
						<div><i class="fa-solid fa-bullhorn" role="button"></i></div>
						<div>
							<h4 class="ps-5">DIGITAL CONSULTING</h4>
							<p class="px-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
					<div class="banking col-6 d-flex flex-row">
						<div>
							<i class="fa-solid fa-wallet" role="button"></i>
						</div>
						<div>
							<h4 class="ps-5">BANKING CONSULTING</h4>
							<p class="px-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
					<div class="enterprise col-6 d-flex flex-row">
						<div><i class="fa-solid fa-minimize" role="button"></i></div>
						<div>
							<h4 class="ps-5">ENTERPRISE CONSULTING</h4>
							<p class="px-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "Consultants",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#consultants {
	color: $black;
	padding: 150px 0;
	background-color: $alfa_color;
	h4 {
		font-size: 22px;
	}
	.highlight {
		width: 100%;
		margin-bottom: 125px;
		margin-right: 0;
	}
	.consults > div {
		padding-bottom: 30px;
	}
}
</style>