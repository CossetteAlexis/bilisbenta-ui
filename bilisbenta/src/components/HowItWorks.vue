<template>
    <section class="section section-2" id="how-it-works">
		<div class="container">
			<div class="text-center" data-aos="fade-down" data-aos-offset="400" data-aos-duration="1000">
				<p class="section-vid-text-1"><span class="text-primary">We've brought more than 50,000 Products</span> to sell in one Roof from different manufacturers and suppliers in to one marketplace.</p>
			</div>
			<div class="text-center" data-aos="fade-down" data-aos-offset="400" data-aos-duration="1000">
				<p class="section-vid-text-2 mt-4 px-5">You can list and sell products without ever having to buy inventory up front or pack and ship orders.</p>
			</div>
			<div class="row my-5 pt-5">
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="500">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">1</div>
							<img src="/img/01.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Sign up and log in</strong></p>
						</div>
					</div>
				</div>
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="800">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">2</div>
							<img src="/img/02.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Free Browsing on all the packages we offer</strong></p>
						</div>
					</div>
				</div>
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="1100">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">3</div>
							<img src="/img/03.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Choose the package that best suits you</strong></p>
						</div>
					</div>
				</div>
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="1400">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">4</div>
							<img src="/img/04.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Review terms and conditions</strong></p>
						</div>
					</div>
				</div>
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="1700">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">5</div>
							<img src="/img/05.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Fill up the requirement forms and details</strong></p>
						</div>
					</div>
				</div>
				<div class="col-md-2 card-group" data-aos="fade-up" data-aos-offset="200" data-aos-duration="2000">
					<div class="card border-0">
						<div class="card-body">
							<div class="num-circle">6</div>
							<img src="/img/06.png" alt="" class="card-img mx-auto d-block mt-4">
							<p class="card-text text-center px-2 mt-4"><strong>Choose a plan for payments and options</strong></p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
    name: "About"
}
</script>

<style scoped>
    .section {
        padding: 100px 0px;
    }

  .num-circle {
    width: 39.6px;
    height: 39.6px;
    border-radius: 50%;
    text-align: center;
    font-size: 20px;
    border: 2px solid rgb(1, 107, 186);
    color:white;
    background:rgb(1, 107, 186);
    position: absolute;
    top: -20px;
    left: 50%;
    transform: translateX(-50%)
    }

  .section-2 {
    background-color: #F4F5F5;
    }

  .section-2 .card-img {
    height: 50px !important;
    width: 50px !important;
    }

    .section-vid-text-1 {
    font-size: 1.9rem;
    font-weight: 600;
    }

  .section-vid-text-2 {
    font-size: 1.6rem;
    font-weight: 500;
    }

</style>