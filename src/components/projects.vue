<template>
  <div class="relative overflow-visible">
    <div class="max-w-screen-xl mx-auto z-10 px-5 md:px-10 xl:px-0">
      <!-- <h1
        class="ftext-4xl lg:text-5xl font-light lg:text-left md:text-center font-medium leading-normal lg:leading-normal text-gray-900"
      >
        Projects
      </h1>
      <p
        class="font-normal text-lg text-gray-500 tracking-normal text-left md:text-center"
        style="letter-spacing: 0.2px"
      >
        We are Agile!! Checkout some of our inhouse developed products.
      </p> -->
      <div class="flex flex-col-reverse lg:flex-row items-center mt-28 mb-10 md:mb-28">
          <div class="w-full lg:w-3/5 space-y-5">
              <h2
                class="text-4xl lg:text-5xl font-light lg:text-left md:text-center font-medium leading-normal lg:leading-normal text-gray-900"
              >
                Jolinow
            </h2>
            <p class="text-lg md:text-xl text-gray-500 lg:text-left md:text-center">
              Jolinow is an experience booking platform for experience creators. It makes it easy for businesses and individuals
              to create and book experiences in simple steps.
            </p>
            <div class="h-20">
              <router-link
                to="/contact"
                class="text-lg font-medium text-blue-700 flex"
                >View details <img src="../assets/arrow.svg" class="w-6 ml-1" alt="laptop" /></router-link
              >
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

    <!-- <div class="w-full grid grid-cols-1 lg:grid-cols-2 gap-x-20 gap-y-10 px-4">
      <div
        class="w-full rounded-xl overflow-hidden shadow border-1 hidden transform hover:scale-105 border-gray-200 border-opacity-75 flex flex-col hover:shadow-lg transition-all ease-linear delay-200 cursor-pointer"
      >
        <div
          class="w-full h-full overflow-hidden flex flex-col md:flex-row items-start bg-gray-100 px-5 lg:px-10 py-10 pb-3"
        >
          <img src="../assets/@ Macbook Pro.png" class="w-[100px] h-auto" alt="laptop" />
        </div>
        <div class="w-full px-5 py-0 md:py-5 md:p-8 pt-0 bg-gray-100">
          <h4
            class="font-semibold tracking-tight leading-normal text-gray-900 md:mt-0 cursor-default"
            style="font-size: 24px"
            title="Ghana Vehicle Import Duty Estimater"
          >
            Ghana Vehicle Import Duty Estimater
          </h4>

          <p
            class="font-normal tracking-normal text-gray-500 mt-3"
            style="font-size: 16px"
          >
            <span
              >Our Web App makes it possible to check the import duty and vehicle
              information about any vehicle you would like to import into Ghana stress
              free and all in one space!</span
            >
          </p>
          <button
            class="text-white py-3 w-full md:w-1/2 mt-5 mb-10 md:mb-0 text-base font-medium rounded-md"
            style="background-color: #b00000"
            @click="dutyCalc('https://ghanadutycalculator.com/estimates')"
            title="ghanadutycalculater.com"
          >
            Visit Site
          </button>
        </div>
      </div>
      <div
        class="w-full rounded-xl overflow-hidden shadow border-1 transform border-gray-200 border-opacity-75 flex flex-col hover:shadow-lg transition-all ease-linear delay-200 cursor-pointer hover:scale-105"
      >
        <div
          class="w-full h-full overflow-hidden flex flex-col items-start bg-gray-100 px-5 lg:px-10 py-10 pb-3"
        >
          <img src="../assets/trippify.png" class="w-[100px] h-auto" alt="laptop" />
        </div>
        <div class="w-full px-5 py-0 md:py-5 md:p-8 pt-0 bg-gray-100">
          <h4
            class="font-semibold tracking-tight leading-normal text-gray-900 md:mt-0 cursor-default"
            style="font-size: 24px"
            title="Ghana Vehicle Import Duty Estimater"
          >
            Jolinow
          </h4>

          <p
            class="font-normal tracking-normal text-gray-500 mt-3"
            style="font-size: 16px"
          >
            <span>
              Jolinow is an online booking platform for experience, tour and ticketing
              businesses. Jolinow makes it easy for you to create and book
              experiences.</span
            >
          </p>
          <button
            class="text-white py-3 w-full md:w-1/2 mt-5 mb-10 md:mb-0 text-base font-medium rounded-md"
            style="background-color: #b00000"
            @click="dutyCalc('https://jolinow.com')"
            title="www.jolinow.com"
          >
            Visit Site
          </button>
        </div>
      </div>
    </div> -->
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
