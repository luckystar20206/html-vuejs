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
			<div class="button btn-transition">
				<a class="read-more btn-transition" href="#">READ MORE</a>
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

	h2 {
		letter-spacing: 3px;
		font-size: 16px;
	}
	p {
		font-family: $secondary-font;
		font-size: 100px;
		font-weight: 700;
		line-height: 90px;
	}
	.highlight {
		margin: 0 15px 5px 0;
		width: 50px;
		border-bottom: 2px solid $aqua;
	}
}
.read-more {
	padding: 25px 50px;
	background-color: $aqua;
	color: $black;
	margin-right: 30px;
	letter-spacing: 3px;
}
.read-more:hover {
	background-color: $red;
	color: $white;
}

.fa-play {
	border: 2px solid $white;
	border-radius: 50%;
	padding: 15px 16px 15px 18px;
	font-size: 16px;
	color: $aqua;
	transform: scale(0.9);
}
.fa-play:hover {
	transform: scale(1);
}
</style>