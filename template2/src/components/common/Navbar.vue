<template>
  <nav class="nav flex flex-wrap items-center justify-between px-4">
    <div class="ml-20">
      <img
        src="https://preview.colorlib.com/theme/allfood/assets/img/logo/logo.png.webp"
        alt=""
      />
    </div>

    <input class="menu-btn hidden" type="checkbox" id="menu-btn" />
    <label
      class="
        menu-icon
        block
        cursor-pointer
        md:hidden
        px-2
        py-4
        relative
        select-none
      "
      for="menu-btn"
    >
      <span class="navicon bg-grey-darkest flex items-center relative"></span>
    </label>

    <ul
      class="
        menu
        border-b
        md:border-none
        flex
        justify-end
        list-reset
        m-0
        w-full
        md:w-auto
        mr-20
      "
    >
      <li class="border-t md:border-none">
        <a
          style="padding: 39px 24px"
          href="/"
          class="
            block
            md:inline-block
            px-4
            py-3
            font-bold
            no-underline
            text-grey-darkest
            hover:text-yellow-500
          "
          >Home</a
        >
      </li>

      <li class="border-t md:border-none">
        <a
          style="padding: 39px 24px"
          href="/about/"
          class="
            block
            md:inline-block
            px-4
            py-3
            font-bold
            no-underline
            text-grey-darkest
            hover:text-yellow-500
          "
          >About</a
        >
      </li>

      <li class="border-t md:border-none">
        <a
          style="padding: 39px 24px"
          href="/blog/"
          class="
            block
            md:inline-block
            px-4
            py-3
            font-bold
            no-underline
            text-grey-darkest
            hover:text-yellow-500
          "
          >Menu</a
        >
      </li>

      <li class="border-t md:border-none">
        <a
          style="padding: 39px 24px"
          href="/blog/"
          class="
            block
            md:inline-block
            px-4
            py-3
            font-bold
            no-underline
            text-grey-darkest
            hover:text-yellow-500
          "
          >Blog</a
        >
      </li>

      <li class="border-t md:border-none">
        <a
          style="padding: 39px 24px"
          href="/blog/"
          class="
            block
            md:inline-block
            px-4
            py-3
            font-bold
            no-underline
            text-grey-darkest
            hover:text-yellow-500
          "
          >Contact</a
        >
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
</style>