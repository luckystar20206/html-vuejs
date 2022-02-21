<template>
	<section id="consultants">
		<div class="d-flex">
			<h3>OUR CONSULTANTS CAN HELP YOU</h3>
			<div class="highlight"></div>
		</div>
		<div class="container">
			<div class="row">
				<div class="consults col-12 d-flex flex-wrap">
					<div
						class="consult-box col-6 d-flex flex-row"
						v-for="(consult, index) in consults"
						:key="index"
					>
						<div>
							<i class="fa-solid" :class="consult.icon" role="button"></i>
						</div>
						<div>
							<h4 class="ps-5">{{ consult.title.toUpperCase() }}</h4>
							<p class="px-5">
								{{ consult.text }}
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
	data() {
		return {
			consults: [
				{
					title: "statistical consulting",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
					icon: "fa-chart-column",
				},
				{
					title: "digital consulting",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
					icon: "fa-bullhorn",
				},
				{
					title: "banking consulting",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
					icon: "fa-wallet",
				},
				{
					title: "enterprise consulting",
					text: "When, while lovely valley teems with vapour around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a",
					icon: "fa-minimize",
				},
			],
		};
	},
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