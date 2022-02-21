<template>
	<div id="footer-spotlight">
		<div class="container h-100">
			<div class="row h-100 justify-content-center text-center">
				<div class="col-6 d-flex align-items-center justify-content-center">
					<div class="spotlight">
						<div class="d-flex align-items-center">
							<h2>LET'S TALK ABOUT WORK</h2>
						</div>
						<p class="px-5">
							A wonderful serenity has taken possession Far far away, behind the
							word mountains.
						</p>
						<div class="pt-5">
							<a class="cs-button btn-transition" href="#">GET STARTED</a>
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

	.spotlight {
		padding-top: 260px;

		p {
			color: $alfa_color;
			letter-spacing: 1px;
		}
		.cs-button {
			background-color: $darkblue;
			color: $alfa_color;
		}
		.cs-button:hover {
			background-color: $psi_color;
			color: $beta_color;
		}
	}
}
</style>