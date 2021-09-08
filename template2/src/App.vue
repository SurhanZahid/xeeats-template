<template>
  <div>
    <Navbar />
    <Banner />
    <div class="grid grid-cols-2 gap-2 mt-40">
      <div class="ml-60">
        <h1 class="color-orange font-bold text-lg block">Discover Your Test</h1>
        <h1 class="font-bold text-5xl block mt-5">We Provide Good Food For Your Family!</h1>
        <h1 class="font-bold text-lg block mt-5 justify-left">Ut enim acgsd minim veniam, quxcis nostrud exercitation ullamco laboris nisi ufsit aliquip ex ea commodo consequat is aute irure m, quis nostrud exer.</h1>
        <div class="grid grid-cols-4 gap-2 mt-40">
          <div class="col-span-2">
            <span class="container"><i class="fas fa-glass-cheers text-3xl pt-2"></i></span>
            <span class="ml-3">Ut enim ad minim veniam, quis nostrud exer.</span>
          </div>
          <div class="col-span-2">2</div>
          <div class="col-span-2">3</div>
          <div class="col-span-2">4</div>
        </div>
      </div>
      <!-- ... -->
      <div>
        <img src="https://preview.colorlib.com/theme/allfood/assets/img/gallery/about.png.webp" alt="">
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./components/common/Navbar.vue";
import Banner from "./components/layouts/Banner.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Banner,
  },
};
</script>

<style>
body {
  font-family: "Josefin Sans", sans-serif;
}
.color-orange{
  color: #ff5600;
}
</style>
