<template>
	<footer>
		<div id="footer-spotlight">
			<div class="container h-100">
				<div class="row h-100 justify-content-center text-center">
					<div class="col-6 d-flex align-items-center justify-content-center">
						<div class="spotlight">
							<div class="d-flex align-items-center">
								<div class="highlight"></div>
								<h2>LET'S TALK ABOUT WORK</h2>
							</div>
							<p class="px-5">
								A wonderful serenity has taken possession Far far away, behind
								the word mountains.
							</p>
							<div class="button pt-5">
								<a class="read-more" href="#">GET STARTED</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<nav>
			<div class="container">
				<div class="row">
					<div
						id="footer-navbar"
						class="d-flex justify-content-between align-items-center"
					>
						<div class="logo" role="button">
							<img src="../assets/images/logotype-2-150x25.png" alt="logo" />
						</div>
						<div class="footer-nav">
							<ul class="list-unstyled d-flex mb-0">
								<li><a href="#">HOME</a></li>
								<li><a href="#">ABOUT</a></li>
								<li><a href="#">PROJECTS</a></li>
								<li><a href="#">SERVICES</a></li>
								<li><a href="#">BLOG</a></li>
								<li><a href="#">CONTACTS</a></li>
							</ul>
						</div>
						<div class="social-icons">
							<i class="fa-brands fa-instagram"></i>
							<i class="fa-brands fa-linkedin-in"></i>
							<i class="fa-brands fa-facebook-f"></i>
							<i class="fa-brands fa-twitter"></i>
						</div>
					</div>
				</div>
				<div class="row">
					<div
						class="
							col
							p-0
							rights
							d-flex
							justify-content-between
							align-items-center
						"
					>
						<div class="d-flex flex-column">
							<span>Terms of use</span>
							<span>Privacy Environmental Policy</span>
						</div>
						<span
							>Copyright © 2022 Phlox Consulting. All Rights Reserved.
						</span>
					</div>
				</div>
			</div>
		</nav>
	</footer>
</template>

<script>
export default {
	name: "Footer",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
footer {
	background-color: $darkblue;
}
#footer-spotlight {
	background-image: url("../assets/images/business-people-working-together-on-project-and-B3MZ4TX.jpg");
	background-repeat: no-repeat;
	background-position: bottom;

	height: 700px;
	color: $white;

	.spotlight {
		padding-top: 260px;

		h2 {
			font-family: $secondary-font;
			font-size: 50px;
			font-weight: 700;
			line-height: 90px;
		}
		.read-more {
			padding: 25px 50px;
			background-color: $darkblue;
			color: $white;
			margin-right: 30px;
			letter-spacing: 3px;
		}
	}
}
#footer-navbar {
	color: $grey;
	height: 200px;
	border-bottom: 1px solid $grey;

	li,
	i {
		padding: 20px 0;
		margin: 0 15px;
		font-weight: 400;
	}
	li:hover a {
		color: $red;
	}
	i {
		color: $white;
		font-size: 18px;
	}
}
.rights {
	color: $grey;
	height: 100px;
	font-size: 14px;
}
</style>