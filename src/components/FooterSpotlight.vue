<template>
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
							A wonderful serenity has taken possession Far far away, behind the
							word mountains.
						</p>
						<div class="button pt-5">
							<a class="read-more btn-transition" href="#">GET STARTED</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "FooterSpotlight",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
#footer-spotlight {
	background-image: url("../assets/images/business-people-working-together-on-project-and-B3MZ4TX.jpg");
	background-repeat: no-repeat;
	background-position: bottom;

	height: 700px;
	color: $alfa_color;

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
			color: $alfa_color;
			margin-right: 30px;
			letter-spacing: 3px;
		}
        .read-more:hover {
            background-color: $psi_color;
            color: $beta_color;
        }
	}
}
</style>