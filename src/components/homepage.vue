<template>
  <div class="relative overflow-visible">
    <div class="absolute right-0 w-1/3 -mt-96 overflow-hidden lg:-mt-56">
      <!-- <img src="../assets/Rectangle.png" class="w-full" alt="" /> -->
      <div
        class="bg-blue-100 rounded-bl-full hidden lg:block"
        style="min-height: 900px; min-width: 800px"
      ></div>
    </div>

    <div
      class="relative max-w-screen-xl mx-auto px-5 md:px-5 z-10"
    >
      <div class="w-full">
        <div class="flex flex-col-reverse lg:flex-row items-center">
          <div class="w-full lg:w-3/5 space-y-6 md:mt-40">
            <h2
              class="text-4xl font-medium leading-normal text-gray-900 xl:max-w-[43.5rem]"
            >
              We are a team of qualified designers and developers with integrity from diverse
              backgrounds, who take responsibility and deliver the best quality work.
          </h2>
            <div class="h-20 pt-5">
              <router-link
                to="/contact"
                class="px-5 py-3 text-white text-lg font-medium bg-blue-700 rounded-lg"
                >Contact Us</router-link
              >
            </div>
          </div>
          <div class="w-full lg:w-2/5 mb-10 lg:mb-0">
            <img
              src="../assets/heroimg.svg"
              class="w-full hidden lg:block"
              alt=""
            />
          </div>
        </div>
      </div>
      <Questions />
      <ourservicesVue />
      <whowearecompVue />

      <!-- <div class="w-full space-y-10 md:space-y-10">
        <div class="bg-transparent">
          <div class="max-w-7xl mx-auto px-0 sm:px-6 lg:px-8">
            <div class="lg:text-center">
              <h1
                class="font-semibold tracking-normal font-gray-900 text-left md:text-center text-3xl md:text-4xl"
              >
                Projects
              </h1>
              <p
                class="text-lg md:text-xl text-gray-500 text-left md:text-center mt-0 md:mt-2"
              >
                We are Agile!! Checkout some of our inhouse developed products
            </p>
            </div>
          </div>
        </div>
        <div class="w-full grid grid-cols-1 md:grid-cols-2 gap-20 md:gap-20">
          <div class="flex flex-col space-x-0 lg:space-x-20 space-y-10 hidden">
            <div class="w-full px-16 md:px-5 rounded-3xl">
              <img
                src="../assets/@ Macbook Pro.png"
                class="w-full max-w-sm mx-auto"
                alt=""
              />
            </div>
            <div class="w-full h-full pl-0 flex flex-col justify-start relative">
              <h2
                class="font-semibold tracking-tight leading-normal text-gray-900"
                style="font-size: 24px"
              >
                Ghana Vehicle Import Duty Estimater
              </h2>
              <p
                class="font-normal tracking-normal text-gray-500 text-left leading-normal text-base pb-1 mb-4 mt-5 max-w-md"
              >
                Our Web App makes it possible to check the import duty and vehicle
                information about any vehicle you would like to import into Ghana stress
                free and all in one space.
              </p>

              <a
                href="https://ghanadutycalculator.com/estimates"
                target="_blank"
                class="w-1/2 md:w-48 text-center py-3 mt-1 font-medium text-base cursor-pointer text-white rounded-md flex items-center justify-center"
                style="background-color: #b00000"
                ><span>Visit Website</span></a
              >
            </div>
          </div>
          <div class="flex flex-col space-x-0 lg:space-x-20 space-y-10">
            <div class="w-full px-16 md:px-5 rounded-3xl">
              <img
                src="../assets/trippify.png"
                class="w-full px-0 max-w-sm mx-auto"
                alt=""
              />
            </div>
            <div class="w-full pl-0 flex flex-col justify-center">
              <h2
                class="font-semibold tracking-tight leading-normal text-gray-900"
                style="font-size: 24px"
              >
                Jolinow
              </h2>
              <p
                class="font-normal tracking-normal text-gray-500 text-left leading-normal text-base pb-1 mb-4 mt-5 max-w-md"
              >
                Jolinow is an online booking platform for experience, tour and ticketing
                businesses. Jolinow makes it easy for you to create and book experiences.
              </p>

              <a
                href="https://jolinow.com"
                target="_blank"
                class="w-1/2 md:w-48 text-center py-3 mt-1 font-medium text-base cursor-pointer text-white rounded-md flex items-center justify-center"
                style="background-color: #b00000"
                ><span>Visit Website</span></a
              >
            </div>
          </div>
        </div>
      </div> -->
    </div>
  </div>
</template>

<script>
import ourservicesVue from "./ourservices.vue";
import whowearecompVue from "./whowearecomp.vue";
import Questions from "./questions.vue";
export default {
  components: {
    ourservicesVue,
    whowearecompVue,
    Questions,
  },
};
</script>

<style>
.heading {
  font-size: 64px;
  line-height: 77px;
}

.herocaption {
  font-size: 20px;
  letter-spacing: 5%;
  line-height: 28px;
}
</style>
