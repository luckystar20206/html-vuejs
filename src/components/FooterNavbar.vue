<template>
	<nav>
		<div class="container">
			<div class="row">
				<div
					id="footer-navbar"
					class="d-flex justify-content-between align-items-center"
				>
					<div class="logo">
						<img src="../assets/images/logotype-2-150x25.png" alt="logo" />
					</div>
					<div class="footer-nav">
						<ul class="list-unstyled d-flex mb-0">
							<li><a class="transition" href="#">HOME</a></li>
							<li><a class="transition" href="#">ABOUT</a></li>
							<li><a class="transition" href="#">PROJECTS</a></li>
							<li><a class="transition" href="#">SERVICES</a></li>
							<li><a class="transition" href="#">BLOG</a></li>
							<li><a class="transition" href="#">CONTACTS</a></li>
						</ul>
					</div>
					<div class="social-icons">
						<i class="fa-brands fa-instagram transition" role="button"></i>
						<i class="fa-brands fa-linkedin-in transition" role="button"></i>
						<i class="fa-brands fa-facebook-f transition" role="button"></i>
						<i class="fa-brands fa-twitter transition" role="button"></i>
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
					<span>Copyright © 2022 Phlox Consulting. All Rights Reserved. </span>
				</div>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: "FooterNavbar",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#footer-navbar {
	color: $omega_color;
	height: 200px;
	border-bottom: 1px solid $omega_color;

	li,
	i {
		padding: 20px 0;
		margin: 0 15px;
		font-weight: 400;
	}
	li:hover a,
	i:hover {
		color: $gamma_color;
	}
	i {
		color: $alfa_color;
		font-size: 18px;
	}
}
.rights {
	height: 100px;
	font-size: 14px;
}
</style>