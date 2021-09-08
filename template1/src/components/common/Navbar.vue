<template>
  <nav class="bg-black opacity-75 z-50 shadow-lg fixed w-full">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between">
        <div class="flex space-x-7">
          <div>
            <!-- Website Logo -->
            <a
              href="#"
              class="
                flex
                items-center
                text-white
                font-semi-bold
                text-3xl text-white
                py-4
                px-2
                pt-5
              "
            >
              Menu.
            </a>
          </div>
        </div>
        <!-- Secondary Navbar items -->
        <div class="hidden md:flex items-center space-x-3">
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('about_section')"
            >about</a
          >
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('whats_on')"
            >what's on</a
          >
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('menu_section')"
            >menu</a
          >
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('gallery')"
            >gallery</a
          >
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('location')"
            >location</a
          >
          <a
            class="
              py-2
              uppercase
              px-2
              font-medium
              text-white
              font-semi-bold
              transition
              duration-300
              cursor-pointer
            "
            @click="onClick('contact_us')"
            >contact us</a
          >

          <button
            class="
              bg-yellow-500
              text-lg text-white
              font-semi-bold
              py-2
              px-7
              rounded
              uppercase
            "
            @click="showRegistration"
          >
            book a table
          </button>
        </div>
        <!-- Mobile menu button -->
        <div class="md:hidden flex items-center">
          <button class="outline-none mobile-menu-button">
            <svg
              class="w-6 h-6 text-gray-500 hover:text-blue-500"
              x-show="!showMenu"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
    <!-- mobile menu -->
    <div class="hidden mobile-menu">
      <ul class="">
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/"
            id="home"
            >About</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/menu"
            id="menu"
            >Whats on</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/about"
            id="about"
            >Menu</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/contact"
            id="about"
            >Gallery</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/contact"
            id="about"
            >Location</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px-2 py-4 text-white font-semibold"
            to="/contact"
            id="about"
            >Contact us</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
</style>