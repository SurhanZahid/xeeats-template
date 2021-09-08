<template>
  <div class="md:flex flex-col md:flex-row w-full mt-5 mb-3">
    <div
      @click="toggle(open)"
      class="
        flex flex-col
        w-full
        md:w-64
        text-gray-700
        dark-mode:text-gray-200 dark-mode:bg-gray-800
        flex-shrink-0
      "
      x-data="{ open: false }"
    >
      <div
        class="
          flex-shrink-0
          px-8
          py-4
          flex flex-row
          items-center
          justify-between
        "
      >
        <a
          href="#"
          class="
            text-xl
            font-semibold
            tracking-widest
            text-gray-900
            uppercase
            rounded-lg
            dark-mode:text-white
            focus:outline-none
            focus:shadow-outline
          "
          >Popular Foods</a
        >
        <button
          class="
            rounded-lg
            md:hidden
            rounded-lg
            focus:outline-none
            focus:shadow-outline
          "
          @click="open = !open"
        >
          <svg fill="currentColor" viewBox="0 0 20 20" class="w-6 h-6">
            <path
              x-show="!open"
              fill-rule="evenodd"
              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM9 15a1 1 0 011-1h6a1 1 0 110 2h-6a1 1 0 01-1-1z"
              clip-rule="evenodd"
            ></path>
            <path
              x-show="open"
              fill-rule="evenodd"
              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
      </div>
      <nav
        :class="{ block: open, hidden: !open }"
        class="flex-grow md:block px-4 pb-4 md:pb-0 md:overflow-y-auto"
      >
        <router-link
          class="
            block
            px-4
            py-2
            mt-2
            text-lg
            font-semibold
            text-gray-900
            bg-transparent
            rounded-lg
            dark-mode:bg-transparent
            dark-mode:hover:bg-gray-600
            dark-mode:focus:bg-gray-600
            dark-mode:focus:text-white
            dark-mode:hover:text-white
            dark-mode:text-gray-200
            hover:text-gray-900
            focus:text-gray-900
            hover:bg-white
            focus:bg-gray-200
            focus:outline-none
            focus:shadow-outline
          "
          @click="display('breakfast')"
          >Breakfast
        </router-link>
        <router-link
          class="
            block
            px-4
            py-2
            mt-2
            text-lg
            font-semibold
            text-gray-900
            bg-transparent
            rounded-lg
            dark-mode:bg-transparent
            dark-mode:hover:bg-gray-600
            dark-mode:focus:bg-gray-600
            dark-mode:focus:text-white
            dark-mode:hover:text-white
            dark-mode:text-gray-200
            hover:text-gray-900
            focus:text-gray-900
            hover:bg-white
            focus:bg-gray-200
            focus:outline-none
            focus:shadow-outline
          "
          @click="display('lunch')"
          >Lunch</router-link
        >
        <router-link
          class="
            block
            px-4
            py-2
            mt-2
            text-lg
            font-semibold
            text-gray-900
            bg-transparent
            rounded-lg
            dark-mode:bg-transparent
            dark-mode:hover:bg-gray-600
            dark-mode:focus:bg-gray-600
            dark-mode:focus:text-white
            dark-mode:hover:text-white
            dark-mode:text-gray-200
            hover:text-gray-900
            focus:text-gray-900
            hover:bg-white
            focus:bg-gray-200
            focus:outline-none
            focus:shadow-outline
          "
          to="/cards"
          >Dinner</router-link
        >
        <router-link
          class="
            block
            px-4
            py-2
            mt-2
            text-lg
            font-semibold
            text-gray-900
            bg-transparent
            rounded-lg
            dark-mode:bg-transparent
            dark-mode:hover:bg-gray-600
            dark-mode:focus:bg-gray-600
            dark-mode:focus:text-white
            dark-mode:hover:text-white
            dark-mode:text-gray-200
            hover:text-gray-900
            focus:text-gray-900
            hover:bg-white
            focus:bg-gray-200
            focus:outline-none
            focus:shadow-outline
          "
          to="/address"
          >Drinks</router-link
        >
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard Sidebar",
  data() {
    return {
      open: false,
    };
  },
  methods: {
    toggle(open) {
      if (!open) {
        open = true;
      } else {
        open = false;
      }
    },
    display(option) {
      if (option === "breakfast") {
        var breakfast = document.getElementsByClassName("breakfast");
        var lunch = document.getElementsByClassName("lunch");
        for (var i = 0; i < breakfast.length; i++) {
          breakfast[i].style.display = "block";
        }
        for (var j = 0; j < lunch.length; j++) {
          lunch[j].style.display = "none";
        }
        // document.getElementsByClassName("breakfast").style.display = "none";
        // document.getElementsByClassName("lunch").style.display = "block";
      } else if (option === "lunch") {
        var breakfast1 = document.getElementsByClassName("breakfast");
        var lunch1 = document.getElementsByClassName("lunch");
        for (var k = 0; k < breakfast1.length; k++) {
          breakfast1[k].style.display = "none";
        }
        for (var l = 0; l < lunch1.length; l++) {
          lunch1[l].style.display = "block";
        }
      }
    },
  },
};
</script>

<style scoped>
</style>