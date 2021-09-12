<template>
  <nav class="bg-white fixed w-full rounded p-4">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between">
        <div class="flex space-x-7">
          <div>
            <!-- Website Logo -->
            <img
              class="py-4 px-2"
              src="https://preview.colorlib.com/theme/sneaky/img/logo.png.webp"
              alt=""
              srcset=""
            />
          </div>
        </div>
        <!-- Secondary Navbar items -->
        <div class="hidden md:flex items-center space-x-3">
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('about_section')"
            >About</a
          >
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('whats_on')"
            >What's on</a
          >
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('menu_section')"
            >Menu</a
          >
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('gallery')"
            >Gallery</a
          >
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('location')"
            >Location</a
          >
          <a
            class="px-3  transition duration-300 cursor-pointer"
            @click="onClick('contact_us')"
            >Contact us</a
          >
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
          <router-link class="block text-sm px font-semibold" to="/" id="home"
            >About</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px font-semibold"
            to="/menu"
            id="menu"
            >Whats on</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px font-semibold"
            to="/about"
            id="about"
            >Menu</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px font-semibold"
            to="/contact"
            id="about"
            >Gallery</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px font-semibold"
            to="/contact"
            id="about"
            >Location</router-link
          >
        </li>
        <li>
          <router-link
            class="block text-sm px font-semibold"
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