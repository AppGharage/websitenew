<template>
  <div class="relative overflow-visible">
    <div class="max-w-screen-xl mx-auto z-10 px-5 md:px-10 xl:px-0">
      <div class="flex flex-col-reverse lg:flex-row items-center mt-28 mb-10 md:mb-28">
          <div class="w-full lg:w-3/5 space-y-5">
              <h2
                class="text-4xl lg:text-5xl font-light font-medium leading-normal lg:leading-normal text-gray-900"
              >
                Jolinow
            </h2>
            <p class="text-lg md:text-xl text-gray-500">
              Jolinow is an experience booking platform for experience creators. It makes it easy for businesses and individuals
              to create and book experiences in simple steps.
            </p>
            <div class="h-20 flex ">
              <a
                href="https://jolinow.com"
                class="text-xl font-medium text-blue-700 flex underline underline-offset-1"
                >View details
              </a>
            </div>
          </div>
          <div class="lg:w-2/5 mt-2 mb-10">
            <img src="../assets/trippify.png" class="w-[100px] h-auto" alt="laptop" />
          </div>
      </div>

      <!-- <div class="flex flex-col lg:flex-row items-center mt-28 mb-10 md:mb-28">
          <div class="lg:w-2/5 mt-2 mr-8">
            <img src="../assets/trippify.png" class="w-[100px] h-auto" alt="laptop" />
          </div>
          <div class="w-full lg:w-3/5 mt-10">
              <h2
                class="text-4xl lg:text-5xl font-light lg:text-left md:text-center font-medium leading-normal lg:leading-normal text-gray-900"
              >
                Jolinow
            </h2>
            <p class="text-lg md:text-xl text-gray-500 lg:text-left md:text-center">
              Jolinow is an experience booking platform for experience creators. It makes it easy for businesses and individuals
              to create and book experiences in simple steps.
            </p>
            <div class="h-20 mt-4">
              <a
                class="text-lg font-medium text-blue-700"
                href="https://jolinow.com"
                >View details <img src="../assets/arrow.svg" class="w-6 ml-1" alt="laptop" />
              </a
              >
            </div>
          </div>
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    dutyCalc: function (x) {
      window.open(x, "_blank");
    },
  },
};
</script>

<style>
.back {
  background-image: url("../assets/dutyestimater.jpg");
  background-position: bottom 50px left 100px;
  background-size: 32%;
  background-attachment: fixed;
  background-repeat: no-repeat;
}
</style>
