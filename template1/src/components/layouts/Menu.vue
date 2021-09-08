<template>
  <section class="py-8 px-4">
    <h1 class="text-4xl font-bold breakfast">Breakfast</h1>
    <h1 class="text-4xl font-bold lunch">Lunch</h1>
    <transition name="slide-fade">
      <div class="flex flex-wrap -mx-4">
        <div id="breakfast" class="px-4 mb-8 md:mb-0 mt-3 breakfast">
          <img
            class="rounded shadow-md img-section"
            src="https://preview.colorlib.com/theme/meal2/images/ximg_1_d.jpg.pagespeed.ic.GsJi6X8mTu.webp"
            alt=""
          />
        </div>
        <div id="breakfast" class="px-4 mb-8 md:mb-0 mt-3 breakfast">
          <img
            class="rounded shadow-md img-section"
            src="https://preview.colorlib.com/theme/meal2/images/ximg_1.jpg.pagespeed.ic.VpbnsnaQH0.webp"
            alt=""
          />
        </div>
        <div id="breakfast" class="px-4 mb-8 md:mb-0 mt-3 breakfast">
          <img
            class="rounded shadow-md img-section"
            src="https://preview.colorlib.com/theme/meal2/images/ximg_4.jpg.pagespeed.ic.rA2X4qH1me.webp"
            alt=""
          />
        </div>
        <div id="breakfast" class="px-4 mb-8 md:mb-0 mt-3 breakfast">
          <img
            class="rounded shadow-md img-section"
            src="https://preview.colorlib.com/theme/meal2/images/ximg_3_b.jpg.pagespeed.ic.v2DnERtnh7.webp"
            alt=""
          />
        </div>
        <div id="lunch" class="px-4 mb-8 md:mb-0 mt-3 lunch">
          <img
            class="rounded shadow-md img-section"
            src="https://images.unsplash.com/photo-1542826438-bd32f43d626f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2056&q=80"
            alt=""
          />
        </div>
        <div id="lunch" class="px-4 mb-8 md:mb-0 mt-3 lunch">
          <img
            class="rounded shadow-md img-section"
            src="https://images.unsplash.com/photo-1546393009-ef37dc6dfd35?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1351&q=80"
            alt=""
          />
        </div>
        <div id="lunch" class="px-4 mb-8 md:mb-0 mt-3 lunch">
          <img
            class="rounded shadow-md img-section"
            src="https://images.unsplash.com/photo-1587314168485-3236d6710814?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1270&q=80"
            alt=""
          />
        </div>
        <div id="lunch" class="px-4 mb-8 md:mb-0 mt-3 lunch">
          <img
            class="rounded shadow-md img-section"
            src="https://preview.colorlib.com/theme/meal2/images/ximg_3_b.jpg.pagespeed.ic.v2DnERtnh7.webp"
            alt=""
          />
        </div>
      </div>
    </transition>
  </section>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style scoped>
.slide-fade-enter-active {
  transition: all 0.3s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.8s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateX(20px);
  opacity: 0;
}
.breakfast {
  display: none;
}
.lunch {
  display: block;
}
.img-section {
  width: 452px;
}
</style>