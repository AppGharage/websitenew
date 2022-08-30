<template>
  <div
    class="max-w-screen-xl mx-auto space-y-5 md:space-y-10 px-5 md:px-10 lg:px-0 mb-24"
  >
    <div>
      <h1
        class="font-bold text-gray-900 text-left md:text-center"
        style="font-size: 40px; letter-spacing: 0.2px"
      >
        Latest Projects
      </h1>
      <p
        class="font-normal text-lg text-gray-500 tracking-normal text-left md:text-center"
        style="letter-spacing: 0.2px"
      >
        Here are the products we have successfully built
      </p>
    </div>

    <div class="w-full grid grid-cols-1 lg:grid-cols-2 gap-x-20 gap-y-10 px-4">
      <div
        class="w-full rounded-xl overflow-hidden shadow border-1 border-gray-200 border-opacity-75 flex flex-col hover:shadow-lg transition-shadow ease-linear delay-200 cursor-pointer"
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
              free and all in one space.</span
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
        class="w-full rounded-xl overflow-hidden shadow border-1 border-gray-200 border-opacity-75 flex flex-col hover:shadow-lg transition-shadow ease-linear delay-200 cursor-pointer"
      >
        <div
          class="w-full h-full overflow-hidden flex flex-col items-start bg-gray-100 px-5 lg:px-10 py-10 pb-3"
        >
          <img src="../assets/trippify.webp" class="w-[100px] h-auto" alt="laptop" />
        </div>
        <div class="w-full px-5 py-0 md:py-5 md:p-8 pt-0 bg-gray-100">
          <h4
            class="font-semibold tracking-tight leading-normal text-gray-900 md:mt-0 cursor-default"
            style="font-size: 24px"
            title="Ghana Vehicle Import Duty Estimater"
          >
            Trippify
          </h4>

          <p
            class="font-normal tracking-normal text-gray-500 mt-3"
            style="font-size: 16px"
          >
            <span>
              Trippify is an online booking platform for experience, tour and ticketing
              businesses. Trippify is to makes it easy for you to create and book
              experiences.</span
            >
          </p>
          <button
            class="text-white py-3 w-full md:w-1/2 mt-5 mb-10 md:mb-0 text-base font-medium rounded-md"
            style="background-color: #b00000"
            @click="dutyCalc('https://trippify.appgharage.com')"
            title="trippify.appgharage.com"
          >
            Visit Site
          </button>
        </div>
      </div>
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
