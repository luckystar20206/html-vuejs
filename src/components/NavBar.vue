<template>
	<div class="col-12">
		<div id="navbar" class="d-flex justify-content-between align-items-center">
			<div class="logo" role="button">
				<img src="../assets/images/logotype.png" alt="logo" />
			</div>
			<div class="nav">
				<ul class="list-unstyled d-flex">
					<li class="active"><a href="#">HOME</a></li>
					<li><a href="#">ABOUT</a></li>
					<li><a href="#">PROJECTS</a></li>
					<li><a href="#">SERVICES</a></li>
					<li><a href="#">BLOG</a></li>
					<li><a href="#">CONTACTS</a></li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "NavBar",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#navbar {
	height: 80px;
	letter-spacing: 0.5px;

	.logo img {
		width: 110px;
		height: auto;
	}
	li {
		padding: 20px 0;
		margin: 0 15px;
		border-top: 5px solid transparent;
		font-weight: 100;
	}
	li.active {
		border-top: 5px solid $white;
		font-weight: 700;
	}
	li:hover {
		border-top: 5px solid $darkblue;
	}
}
</style>