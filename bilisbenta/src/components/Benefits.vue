<template>
    <div>
        <section class="section bg-white" id="benefits">
		<div class="container" data-aos="zoom-in" data-aos-offset="400" data-aos-duration="1000">
			<p class="section-vid-text-1">
				<span class="text-primary">REGISTER FOR FREE!</span> No Credit Card Needed <span class="float-right"><a href="" class="btn btn-lg btn-primary py-3 px-5">Get Started</a></span>
			</p>
		</div>
	</section>
    <section class="section section-3">
		<div class="container text-center">
			<div data-aos="zoom-in-up" data-aos-offset="200" data-aos-duration="300">
				<p class="section-vid-text-1">Why you should choose <span class="text-primary">BilisBenta?</span></p>
			</div>
			<div class="row check-mark text-left">
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="200" data-aos-duration="500">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">No manpower needed</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="200" data-aos-duration="700">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">No warehouse rental</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="200" data-aos-duration="900">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">No capital on inventory</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="200" data-aos-duration="1100">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">No overhead expenses</p></div>
					</div>
				</div>
			</div>
			<div class="row mt-5 text-left">
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="100" data-aos-duration="1300">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">No accounting needed</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="100" data-aos-duration="1500">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">Great product sourcing</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="100" data-aos-duration="1700">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">Milti category products</p></div>
					</div>
				</div>
				<div class="col-md-3" data-aos="zoom-in-up" data-aos-offset="100" data-aos-duration="1900">
					<div class="row">
						<div class="col-md-3 pt-4"><img src="/img/check-mark.png" alt="" class="img-fluid"></div>
						<div class="col-md-9"><p class="section-vid-text-2">Everyone can sell</p></div>
					</div>
				</div>
			</div>
		</div>
	</section>
    <div class="parallax-mid-image">
		<div class="container" data-aos="zoom-in-right" data-aos-offset="400" data-aos-duration="1000">
			<div class="row para-mid-card">
				<div class="col-md-6">
					<div class="para-box px-5">
						<p class="section-vid-text-1">Find everything you need from one Supplier account</p>
						<p class="section-vid-text-2">With Bilisbenta you don't need to signup with suppliers. In fact you can perform all the tasks from selling products, to processing orders nad Chatting you customers</p>
						<a href="" class="btn btn-lg btn-outline-primary py-3 px-5 mt-2">Get Started</a>
					</div>
				</div>
			</div>
		</div>
	</div>
    </div>
</template>

<script>
export default {
    name: "Benefits"
}
</script>

<style scoped>
    .section {
    padding: 100px 0px;
    }

   .section-vid-text-1 {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

  .section-vid-text-1 {
    font-size: 1.9rem;
    font-weight: 600;
    }

    .section-3 img {
    height: 40px !important;
    width: 40px !important;
    background-color: #F4F5F5;
    }

  .check-mark {
    padding-top: 100px;
    }

    .parallax-mid-image {
    background-image: url('/img/benefits-background.png');
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    }

  .para-mid-card .para-box {
    padding: 10em 0px;
    height: 100vh;
    background-color: white;
    opacity: 0.8;
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