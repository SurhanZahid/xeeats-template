<template>
  <Navbar />
  <Banner />
  <About />
  <Dishes />
  <Reservation />
  <Footer />
</template>

<script>
import Navbar from "./components/common/Navbar.vue";
import Footer from "./components/common/Footer.vue";
import Banner from "./components/layouts/Banner.vue";
import About from "./components/layouts/About.vue";
import Reservation from "./components/layouts/Reservation.vue";
import Dishes from "./components/layouts/Dishes.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Banner,
    About,
    Reservation,
    Dishes,
    Footer
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com");
@import url("https://fonts.gstatic.com");
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap");
@import url("https://pro.fontawesome.com/releases/v5.10.0/css/all.css");
body {
  font-family: "Josefin Sans", sans-serif !important;
}

</style>
