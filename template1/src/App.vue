<template>
  <div>
    <Navbar />
    <Banner />
    <main style="background-color: #fee2b3" class="flex py-20">
      <div class="flex flex-col justify-start w-1/4">
        <Sidebar class="ml-12" />
      </div>
      <div class="flex flex-col justify-between w-3/4">
        <Menu />
      </div>
    </main>
    <main
      style="background-color: #fee2b3"
      class="text-center py-20 text-center"
    >
      <h1 class="text-sm font-bold block">CHOOSE DESSERTS</h1>
      <h1 class="text-4xl font-bold block">Popular Desserts</h1>

      <section class="container my-12 w-screen">
        <div
          class="
            w-screen
            flex flex-wrap
            content-center
            justify-around
            my-12
            mx-auto
            px-2
            py-5
            md:px-6
          "
        >
          <article
            class="bg-white overflow-hidden rounded-lg shadow-lg w-64 m-4"
          >
            <a class="" href="#">
              <img
                alt="Placeholder"
                class="h-48 w-full"
                src="https://images.unsplash.com/photo-1616541823729-00fe0aacd32c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1302&q=80"
              />
            </a>

            <div class="rounded-lg bg-white relative -mt-2 p-4">
              <header class="leading-tight mb-2">
                <h1 class="text-lg font-bold">
                  <a class="no-underline hover:underline text-black" href="#">
                    Retos
                  </a>
                </h1>
              </header>

              <p class="leading-tight pb-2 md:pb-4">
                Quincenalmente nos reunimos via Zoom para discutir retos de
                programación a los que previamente acordamos. También hacemos
                Hackathons.
              </p>
            </div>
          </article>
          <!-- END Article1 -->

          <!-- Article2 -->
          <article
            class="bg-white overflow-hidden rounded-lg shadow-lg w-64 m-4"
          >
            <a class="" href="#">
              <img
                alt="Placeholder"
                class="h-48 w-full"
                src="https://images.unsplash.com/photo-1584982890941-b788ae5a54df?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1286&q=80"
              />
            </a>

            <div class="rounded-lg bg-white relative -mt-2 p-4">
              <header class="leading-tight mb-2">
                <h1 class="text-lg font-bold">
                  <a class="no-underline hover:underline text-black" href="#">
                    Colaboración Educativa
                  </a>
                </h1>
              </header>

              <p class="leading-tight pb-2 md:pb-4">
                Brindamos tutoriales y compartimos material educativo. La idea
                es aprender juntes sobre todo tipo de tecnologias.
              </p>
            </div>
          </article>
          <!-- END Article2 -->

          <!-- Article3 -->
          <article
            class="bg-white overflow-hidden rounded-lg shadow-lg w-64 m-4"
          >
            <a class="" href="#">
              <img
                alt="Placeholder"
                class="h-48 w-full"
                src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1280&q=80"
              />
            </a>

            <div class="rounded-lg bg-white relative -mt-2 p-4">
              <header class="leading-tight mb-2">
                <h1 class="text-lg font-bold">
                  <a class="no-underline hover:underline text-black" href="#">
                    Apoyo
                  </a>
                </h1>
              </header>

              <p class="leading-tight pb-2 md:pb-4">
                Hablamos sobre las dificultades en el gremio y discutimos sobre
                nuestros derechos en un mundo donde somos la minoria.
              </p>
            </div>
          </article>
          <!-- END Article3 -->

          <!-- Article3 -->
          <article
            class="bg-white overflow-hidden rounded-lg shadow-lg w-64 m-4"
          >
            <a class="" href="#">
              <img
                alt="Placeholder"
                class="h-48 w-full"
                src="https://images.unsplash.com/photo-1588195538326-c5b1e9f80a1b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=947&q=80"
              />
            </a>

            <div class="rounded-lg bg-white relative -mt-2 p-4">
              <header class="leading-tight mb-2">
                <h1 class="text-lg font-bold">
                  <a class="no-underline hover:underline text-black" href="#">
                    Apoyo
                  </a>
                </h1>
              </header>

              <p class="leading-tight pb-2 md:pb-4">
                Hablamos sobre las dificultades en el gremio y discutimos sobre
                nuestros derechos en un mundo donde somos la minoria.
              </p>
            </div>
          </article>
          <!-- END Article3 -->
        </div>
      </section>
    </main>
    <div
      style="background: rgba(245, 201, 126, 0.9)"
      class="bg-gray-100 pt-5 pb-5 flex items-center"
    >
      <div
        class="
          container
          mx-auto
          max-w-xl
          shadow-md
          hover:shadow-lg
          transition
          duration-300
        "
      >
        <div class="py-12 p-10 bg-white rounded-xl">
          <h1 class="uppercase font-bold text-4xl mb-3 block text-yellow-500">
            reserve a table
          </h1>
          <p class="text-base mb-3">
            For reservation of 8 or more people, please call us on
            <strong>09876543212</strong> or email
            <strong>pizzaria@resturant.com</strong> and we will be happy to
            discuss your booking.
          </p>
          <form class="w-full max-w-lg mt-2">
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                <label
                  class="
                    block
                    uppercase
                    tracking-wide
                    text-gray-700 text-xs
                    font-bold
                    mb-2
                  "
                  for="grid-first-name"
                >
                  First Name
                </label>
                <input
                  class="
                    appearance-none
                    block
                    w-full
                    bg-gray-200
                    text-gray-700
                    border border-gray-200
                    rounded
                    py-3
                    px-4
                    leading-tight
                    focus:outline-none
                    focus:bg-white
                    focus:border-gray-500
                  "
                  id="first-name"
                  type="text"
                />
              </div>

              <div class="w-full md:w-1/2 px-3">
                <label
                  class="
                    block
                    uppercase
                    tracking-wide
                    text-gray-700 text-xs
                    font-bold
                    mb-2
                  "
                  for="grid-last-name"
                >
                  Last Name
                </label>
                <input
                  class="
                    appearance-none
                    block
                    w-full
                    bg-gray-200
                    text-gray-700
                    border border-gray-200
                    rounded
                    py-3
                    px-4
                    leading-tight
                    focus:outline-none
                    focus:bg-white
                    focus:border-gray-500
                  "
                  id="grid-last-name"
                  type="text"
                />
              </div>
            </div>
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                <label
                  class="
                    block
                    uppercase
                    tracking-wide
                    text-gray-700 text-xs
                    font-bold
                    mb-2
                  "
                  for="grid-first-name"
                >
                  Email
                </label>
                <input
                  class="
                    appearance-none
                    block
                    w-full
                    bg-gray-200
                    text-gray-700
                    border border-gray-200
                    rounded
                    py-3
                    px-4
                    leading-tight
                    focus:outline-none
                    focus:bg-white
                    focus:border-gray-500
                  "
                  id="grid-first-name"
                  type="email"
                />
              </div>

              <div class="w-full md:w-1/2 px-3">
                <label
                  class="
                    block
                    uppercase
                    tracking-wide
                    text-gray-700 text-xs
                    font-bold
                    mb-2
                  "
                  for="grid-last-name"
                >
                  Phone
                </label>
                <input
                  class="
                    appearance-none
                    block
                    w-full
                    bg-gray-200
                    text-gray-700
                    border border-gray-200
                    rounded
                    py-3
                    px-4
                    leading-tight
                    focus:outline-none
                    focus:bg-white
                    focus:border-gray-500
                  "
                  id="grid-last-name"
                  type="text"
                />
              </div>
            </div>
            <div class="flex flex-wrap mb-6">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  text-gray-700 text-xs
                  font-bold
                  mb-2
                "
                for="grid-city"
              >
                Date
              </label>
              <input
                class="
                  appearance-none
                  block
                  w-full
                  bg-gray-200
                  text-gray-700
                  border border-gray-200
                  rounded
                  py-3
                  px-4
                  leading-tight
                  focus:outline-none
                  focus:bg-white
                  focus:border-gray-500
                "
                id="grid-city"
                type="date"
              />
            </div>

            <div class="flex flex-wrap mt-2 mb-6">
              <label
                class="
                  block
                  uppercase
                  tracking-wide
                  text-gray-700 text-xs
                  font-bold
                  mb-2
                "
                for="grid-city"
              >
                Special Instructions
              </label>
              <textarea
                class="
                  appearance-none
                  block
                  w-full
                  bg-gray-200
                  text-gray-700
                  border border-gray-200
                  rounded
                  py-3
                  px-4
                  leading-tight
                  focus:outline-none
                  focus:bg-white
                  focus:border-gray-500
                "
                rows="4"
              ></textarea>
            </div>
          </form>
          <button
            class="
              bg-yellow-500
              font-bold
              py-3
              text-sm text-white
              uppercase
              mt-2
              rounded
              w-full
            "
          >
            reserve your table now
          </button>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "../src/components/common/Navbar.vue";
import Footer from "../src/components/common/Footer.vue";
import Banner from "../src/components/layouts/Banner.vue";
import Sidebar from "../src/components/layouts/Sidebar.vue";
import Menu from "../src/components/layouts/Menu.vue";
export default {
  name: "App",
 
  components: {
    Navbar,
    Banner,
    Sidebar,
    Menu,
    Footer,
  },
};
</script>

<style>
.banner-image {
  background-image: url("https://preview.colorlib.com/theme/meal2/images/xhero_bg.jpg.pagespeed.ic.08xBTGP0Gm.webp") !important;
  background-size: cover;
  background-position: center center;
  height: 900px;
  width: 100%;
  color: white;
  box-shadow: inset 0 0 0 2000px rgba(15, 9, 7, 0.3);
}
.banner-heading {
  margin-top: 300px;
}
body {
  font-family: "IBM Plex Sans Arabic", sans-serif;
}
.img-section {
  height: 250px;
}
</style>
