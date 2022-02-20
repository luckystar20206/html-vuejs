<template>
	<section id="consultants">
		<div class="d-flex">
			<h3>OUR CONSULTANTS CAN HELP YOU</h3>
			<div class="highlight"></div>
		</div>
		<div class="container">
			<div class="row">
				<div class="col-6">
					<div class="statistical d-flex flex-row">
						<div>
							<i class="fa-solid fa-chart-column" role="button"></i>
						</div>
						<div>
							<h4 class="ps-5">STATISTICAL CONSULTING</h4>
							<p class="ps-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
					<div class="banking d-flex flex-row">
						<div>
							<i class="fa-solid fa-wallet" role="button"></i>
						</div>
						<div>
							<h4 class="ps-5">BANKING CONSULTING</h4>
							<p class="ps-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="digital d-flex flex-row">
						<div><i class="fa-solid fa-bullhorn" role="button"></i></div>
						<div>
							<h4 class="ps-5">DIGITAL CONSULTING</h4>
							<p class="ps-5">
								When, while lovely valley teems with vapour around meand eridian
								sun strikes the upper impenetrable foliage of my trees, and but
								a
							</p>
						</div>
					</div>
					<div class="enterprise d-flex flex-row">
						<div><i class="fa-solid fa-minimize" role="button"></i></div>
						<div>
							<h4 class="ps-5">ENTERPRISE CONSULTING</h4>
							<p class="ps-5">
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
	padding: 150px 0;
	h3 {
		padding-left: 300px;
		padding-bottom: 100px;
		width: 70%;
		font-size: 30px;
		font-family: $secondary-font;
		font-weight: 600;
	}
	h4 {
		font-family: $secondary-font;
		font-weight: 600;
	}
	p {
		color: $grey;
	}
	.highlight {
		width: 100%;
		margin-bottom: 125px;
		border-bottom: 4px solid $aqua;
	}
	.fa-solid {
		padding: 25px 25px;
		font-size: 28px;
		background-color: $red;
		border-radius: 50%;
		color: $white;
	}
}
.statistical,
.digital {
	padding-bottom: 100px;
}
</style>