<template>
  <div>
    <Navbar />
    <Banner />
    <Discover />
    <About />
    <Blog />
    <Reservation />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/common/Navbar.vue";
import Footer from "./components/common/Footer.vue";
import Banner from "./components/layouts/Banner.vue";
import Discover from "./components/layouts/Discover.vue";
import About from "./components/layouts/About.vue";
import Blog from "./components/layouts/Blog.vue";
import Reservation from "./components/layouts/Reservation.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Banner,
    Discover,
    About,
    Blog,
    Reservation,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com");
@import url("https://fonts.gstatic.com");
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap");
@import url("https://pro.fontawesome.com/releases/v5.10.0/css/all.css");
body {
  font-family: "Josefin Sans", sans-serif;
}
.color-orange {
  color: #ff5600;
}
footer {
  background-image: url("https://preview.colorlib.com/theme/allfood/assets/img/gallery/section_bg02.png.webp") !important;
  background-size: cover;
  background-position: center center;
}
</style>
