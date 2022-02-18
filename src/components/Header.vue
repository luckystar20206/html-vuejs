<template>
	<header>
		<div class="container">
			<div class="row">
				<div class="col">
					<div
						id="navbar"
						class="d-flex justify-content-between align-items-center"
					>
						<div class="logo">
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
			</div>
		</div>
	</header>
</template>

<script>
export default {
	name: "Header",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
header {
	background-image: url("../assets/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
	background-repeat: no-repeat;
	background-position: top right;
	background-color: $bg-darkblue;
	background-size: 1270px;
	height: 100vh;
	color: $text-white;

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
			border-top: 5px solid $text-white;
			font-weight: 700;
		}
		li:hover {
			border-top: 5px solid $text-darkblue;
		}
	}
}
</style>