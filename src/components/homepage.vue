<template>
  <div class="relative overflow-visible">
    <div class="max-w-screen-xl px-5 md:px-10 xl:px-0 mx-auto z-10">
      <div class="w-full">
        <div class="flex lg:flex-row items-center">
          <div class="w-full lg:w-3/5 space-y-5 lg:mt-24 md:mt-10">
            <h2 class="text-4xl lg:text-5xl font-light md:text-left font-semibold leading-normal lg:leading-normal text-gray-900">
                <!-- We are a team of qualified designers and developers with integrity from diverse
                backgrounds, who take responsibility and deliver the best quality work. -->
                Software Development <span class="text-blue-600">&</span> Consulting
            </h2>
            <p class="text-lg md:text-xl text-gray-500 lg:text-left mt-0 md:mt-2">
              Providing the simplest solution for the most complex problem.
            </p>
            <div class="h-20 pt-5 items-center">
              <router-link
                to="/contact"
                class="shadow-lg px-5 py-3 text-white text-lg font-medium bg-blue-700 rounded-br-2xl"
                >Let's Talk !</router-link
              >
            </div>
          </div>
          <div class="lg:w-2/5 m-2">
            <img
              src="../assets/hero2.gif"
              class="w-96 lg:w-full hidden md:block"
              alt=""
            />
          </div>
        </div>
      </div>
      <ourservices />
      <ourapproach />
      <whoweare />
      <!-- <Questions /> -->
    </div>
  </div>
</template>

<script>
import ourservices from "./ourservices.vue";
import ourapproach from "./ourapproach.vue";
import whoweare from "./whoweare.vue";
// import Questions from "./questions.vue";
export default {
  components: {
    ourservices,
    ourapproach,
    whoweare,
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
