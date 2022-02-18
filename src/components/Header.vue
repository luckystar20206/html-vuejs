<template>
	<header>
		<div class="container">
			<div class="row">
				<div class="col-12">
					<div
						id="navbar"
						class="d-flex justify-content-between align-items-center"
					>
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
				<div class="col-5">
					<div id="spotlight">
						<div class="d-flex align-items-center">
							<div class="highlight"></div>
							<h2>ALWAYS THE BEST WAY YOU NEED IT</h2>
						</div>
						<p class="pt-3">THE BEST BUSINESS CONSULTING</p>
					</div>
					<div class="d-flex align-items-center">
						<div class="button">
							<a class="read-more" href="#">READ MORE</a>
						</div>
						<i class="fa-solid fa-play" role="button"></i>
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
	height: 1000px;
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
	#spotlight {
		padding: 240px 0 50px 0;
		position: relative;

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
			border-bottom: 2px solid $text-aqua;
		}
	}
	.read-more {
		padding: 25px 50px;
		background-color: $bg-aqua;
		color: $text-black;
		margin-right: 30px;
		letter-spacing: 3px;
	}
	.fa-play {
		border: 2px solid $text-white;
		border-radius: 50%;
		padding: 15px 16px 15px 18px;
		font-size: 16px;
		color: $text-aqua;
	}
}
</style>