<template>
  <div class="relative overflow-visible max-w-screen-full bg-gray-200">
    <div class="max-w-screen-xl mx-auto">
      <div class="rounded-2xl py-10 md:py-0">
        <div
          class="flex flex-col-reverse lg:flex-row items-start px-0 md:px-10 md:items-center"
        >
        <div
            class="w-full lg:w-2/3 space-y-7 md:py-14 justify-center"
          >
            <h2
              class="font-medium text-3xl lg:text-4xl text-gray-900 leading-normal lg:leading-normal text-left lg:text-left p-3 lg:p-0"
            >
              We are here to help you reach your business goals with future-ready software solutions.
            </h2>
            
            <div class="flex">
              <img src="../assets/creative 1.svg" alt="" class="h-10 w-10 mr-3">
              <div class="">
                <h2 class="font-medium text-xl">
                  Get a world-class standard software
                </h2>
              </div>
            </div>
            <div class="flex">
              <img src="../assets/creative 1.svg" alt="" class="h-10 w-10 mr-3">
              <div class="">
                <h2 class="font-medium text-xl">
                    Get strategic advice
                </h2>
              </div>
            </div>
            <div class="flex">
              <img src="../assets/creative 1.svg" alt="" class="h-10 w-10 mr-3">
              <div class="">
                <h2 class="font-medium text-xl">
                  Modernize legacy software
                </h2>
              </div>
            </div>

            <div class="h-20 pt-5 ml-3 lg:ml-0">
              <router-link
                to="/contact"
                class="px-5 py-3 text-white text-lg font-medium bg-blue-700 rounded-br-2xl"
                >Got an Idea ? Let's Talk !</router-link
              >
            </div>
          </div>
          <!-- <div class="items-center w-full md:w-1/3 py-0 md:py-10 hidden lg:flex">
            <img src="../assets/ctaimage.svg" class="mx-auto" alt="" />
          </div> -->
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
