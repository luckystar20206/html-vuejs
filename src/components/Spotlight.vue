<template>
	<div class="col-5">
		<div id="spotlight">
			<div class="d-flex align-items-center">
				<div class="highlight"></div>
				<h2>ALWAYS THE BEST WAY YOU NEED IT</h2>
			</div>
			<p class="pt-3">THE BEST BUSINESS CONSULTING</p>
		</div>
		<div class="d-flex align-items-center">
			<div>
				<a class="cs-button btn-transition" href="#">READ MORE</a>
			</div>
			<i class="fa-solid fa-play transition" role="button"></i>
		</div>
	</div>
</template>

<script>
export default {
	name: "Spotlight",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";

#spotlight {
	padding: 240px 0 50px 0;
}

.cs-button {
	background-color: $psi_color;
	color: $black;
	margin-right: 30px;
}
.cs-button:hover {
	background-color: $gamma_color;
	color: $alfa_color;
}
</style>