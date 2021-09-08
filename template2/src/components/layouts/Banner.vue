<template>
  <div class="container-fluid">
    <div class="banner-image bg-fixed">
      <div class="flex justify-left ml-80">
        <h1
          class="
            text-lg
            font-bold
            block
            banner-heading
            sm:flex-col
            text-left text-yellow-500
          "
        >
          Discover Your Teste
        </h1>
      </div>
      <div class="grid grid-cols-2 justify-left ml-80">
        <h1
          style="font-size: 70px"
          class="font-extrabold mt-2 sm:flex-col text-left"
        >
          We belive good food offer great smile
        </h1>
      </div>
      <div class="grid grid-cols-2 justify-left ml-80">
        <p class="text-lg mt-5 mt-5 md:justify-left">
          Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
          nisi ut aliquip ex ea commodo consequat is aute irure.
        </p>
      </div>
      <div class="flex justify-left ml-80 mt-10 text-white">
        <button
          class="
            bg-yellow-500
            text-white
            font-semi-bold
            py-2
            px-7
            rounded
            font-bold
            reservation
          "
        >
          Reservation
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.banner-image {
  background-image: url("https://preview.colorlib.com/theme/allfood/assets/img/hero/h1_hero.png.webp") !important;
  background-size: cover;
  background-position: center center;
  height: 900px;
  width: 100%;
  color: black;
}
.banner-heading {
  margin-top: 300px;
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