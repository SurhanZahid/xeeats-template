<template>
  <div class="pt-5 pb-5 flex items-center bg-gray-100">
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
      <div class="py-12 p-10 bg-white rounded-xl reservation">
        <h1 class="uppercase font-bold text-4xl mb-3 block">reserve a table</h1>
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
            reservation-button
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
</template>

<script>
export default {};
</script>

<style scoped>
.reservation {
  color: #8b6052;
}
.reservation-button {
  background: #8b6052;
}
</style>