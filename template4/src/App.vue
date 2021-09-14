<template>
  <Navbar />
  <Banner />
  <Story />
  <Menu />
  <Reservation />
  <Footer />
</template>

<script>
import Navbar from "./components/common/Navbar.vue";
import Footer from "./components/common/Footer.vue";
import Banner from "./components/layouts/Banner.vue";
import Story from "./components/layouts/Story.vue";
import Menu from "./components/layouts/Menu.vue";
import Reservation from "./components/layouts/Reservation.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Banner,
    Story,
    Menu,
    Reservation,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Suranna&display=swap");
body {
  font-family: "Suranna", serif !important;
}
</style>
