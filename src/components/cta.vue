<template>
  <div class="relative overflow-visible max-w-screen-full bg-gray-200">
    <div class="max-w-screen-xl mx-auto">
      <div class="rounded-2xl py-10 md:py-0">
        <div
          class="flex flex-col-reverse lg:flex-row items-start px-0 md:px-10 md:items-center"
        >
          <div
            class="w-full lg:w-2/3 space-y-7 md:py-14 h-full flex flex-col justify-center"
          >
            <h2
              class="font-medium text-4xl lg:text-6xl text-gray-900 leading-normal text-center lg:text-left"
            >
              We are here to make your Business <span class="">Awesome</span>
            </h2>
            <router-link
              to="/contact"
              class="w-full md:w-56 mx-auto lg:mx-0 font-medium text-center rounded-md py-3 text-base text-white bg-blue-700"
              >Let's Talk !</router-link
            >
          </div>
          <div class="items-center w-full md:w-1/3 py-0 md:py-10 hidden lg:flex">
            <img src="../assets/ctaimage.svg" class="mx-auto" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    ctaimg: String,
  },
};
</script>

<style>
.main {
  font-size: 53px;
  line-height: 53px;
}
</style>
