<template>
  <div
    class="
      grid
      md:grid-cols-3
      sm:grid-cols-1
      gap-2
      pt-40
      p-10
      justify-center
      story
    "
  >
    <div class="float-right">
      <img
        class="float-right"
        src="http://www.pixel-industry.com/html/royal-plate/img/pics/spices-left.png"
        alt=""
        srcset=""
      />
    </div>
    <div>
      <div class="frame-box custom-img-background bkg-img2">
        <div class="custom-heading style-1">
          <h3 class="text-center text-5xl"><span>Our story</span></h3>
          <h3 class="text-center text-2xl mb-5">Love for food</h3>

          <!-- .divider.style-1 start -->
          <div class="divider style-1 center">
            <span class="hr-simple left"></span>
            <i class="fa fa-circle hr-icon"></i>
            <span class="hr-simple right"></span>
          </div>
        </div>
        <!-- .custom-heading.style-1 end -->

        <p class="text-center text-xl">
          Welcome. This is Royal plate. Elegant &amp; sophisticated restaurant
          template. Royal plate offers different home page layouts with smart
          and unique design, showcasing beautifully designed elements every
          restaurant website should have. Smooth animations, fast loading and
          engaging user experience are just some of the features this template
          offers. <br />So, give it a try and dive into a world of royal
          restaurant websites.
        </p>
      </div>
    </div>
    <div>
      <img
        src="http://www.pixel-industry.com/html/royal-plate/img/pics/spices-right.png"
        alt=""
        srcset=""
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.story {
  background-image: url("http://www.pixel-industry.com/html/royal-plate/img/pics/bkg-img1.jpg") !important;
  background-size: cover;
  background-position: center center;
  height: 500px;
  width: 100%;
}
.custom-img-background.frame-box {
    background-size: 100%;
    background-position: center;
}
.frame-box {
    background-color: #fff;
    border: 17px solid #131822;
    padding: 125px 80px;
    box-shadow: 0 0 18px 7px rgb(0 0 0 / 30%);
    -moz-box-shadow: 0 0 18px 7px rgba(0,0,0,0.3);
    -webkit-box-shadow: 0 0 18px 7px rgb(0 0 0 / 30%);
}
</style>