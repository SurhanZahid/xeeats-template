<template>
  <div class="container-fluid">
    <div class="banner-image bg-fixed">
      <div class="flex justify-left ml-80">
        <h1
          class="
            text-2xl
            font-semibold
            block
            banner-heading
            sm:flex-col
            text-left text-white
          "
        >
          Discover
        </h1>
      </div>
      <div class="grid grid-cols-2 justify-left ml-80">
        <h1
          style="font-size: 70px"
          class=" mt-2 text-white sm:flex-col text-left"
        >
          We belive good food offer great smile
        </h1>
      </div>
      <div class="grid grid-cols-2 justify-left ml-80">
        <p class="text-lg text-white mt-5 mt-5 md:justify-left">
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
          nisi ut aliquip ex ea commodo consequat is aute irure.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.banner-image {
  background-image: url("http://www.pixel-industry.com/html/royal-plate/img/pics/bkg-img3.jpg") !important;
  background-size: cover;
  background-position: center center;
  height: 800px;
  width: 100%;
  color: black;
  box-shadow: inset 0 0 0 2000px rgba(15, 9, 7, 0.3);
}
.banner-heading {
  margin-top: 200px;
}
.reservation {
  background: #ff5600;
  padding: 27px 44px;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  font-size: 18px;
  border-radius: 6px;
  -moz-user-select: none;
  font-weight: 400;
  letter-spacing: 1px;
  line-height: 0;
  margin-bottom: 0;
  margin: 10px;
  cursor: pointer;
  transition: color 0.4s linear;
  position: relative;
  z-index: 1;
  border: 0;
  overflow: hidden;
  margin: 0;
}
</style>