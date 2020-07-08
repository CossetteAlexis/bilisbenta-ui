<template>
    <div class="image-parallax" id="home">
		<div class="container">
			<div class="para-text" data-aos="fade-right" data-aos-offset="400" data-aos-duration="1000">
				<p class="mb-0">Online Selling</p>
				<p class="text-primary">Made Easy.</p>
			</div>
			<div class="para-text-2" data-aos="fade-left" data-aos-offset="200" data-aos-duration="1000">
				<p class="m-0">Your ONE STOP SHOP</p>
				<p class="m-0">for all your Online Selling.</p>
			</div>
			<div data-aos="flip-right" data-aos-duration="1000">
				<a href="" class="btn btn-lg btn-primary py-3 px-5 mt-3">Get Started</a>
			</div>
		</div>
	</div>
</template>

<script>
export default {
    name: "Home"
}
</script>

<style  scroped>
    .image-parallax {
        background-image: url('/img/home-background.png');
        height: 100vh;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
    }
    .para-text {
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 58px;
    padding-top: 150px;
    font-weight: 700;
    font-size: 3.5rem;
    }

  .para-text-2 {
    font-size: 1.3rem;
    font-weight: 600 !important;
    }
</style>