<template>
  <div class="max-w-screen-xl mx-auto px-5 md:px-10 xl:px-0 space-y-16 md:space-y-24">
    <div class="flex flex-col md:flex-row space-y-10 md:space-y-0">
      <div class="space-y-5 w-full md:w-1/2 flex flex-col">
        <div class="my-0 md:my-auto">
          <h2 class="text-base text-red-700 font-semibold tracking-wide uppercase hidden">
            About
          </h2>
          <h1
            class="font-bold text-gray-900 text-left leading-10"
            style="font-size: 40px; letter-spacing: 0.1px"
          >
            Software Development and Tech Solutions Consulting
          </h1>
          <p
            class="font-normal text-lg text-gray-500 tracking-normal mt-3"
            style="letter-spacing: 0.2px; font-size: 18px"
          >
            With our founders having a great track record of leading tech communities and
            working as great developers. Not forgetting the fact that they were also part
            of the founders of Epay. Our Agile approach to product development makes us
            fit most if not all organizations needs. We follow the best practices for
            product development and software development in order to accelerate product
            development schedules while building the solution for your business. We work
            closely with you to develop an approach that works for your company – no
            matter the size. We develop the entire project along with you to create a
            common floor that achieves measurable software development goals.
          </p>
        </div>
      </div>
      <div class="w-full md:w-1/2 pl-0 lg:pl-20 hidden md:flex">
        <img src="../assets/amico.svg" class="h-full" alt="" />
      </div>
    </div>
    <Team />
    <div class="w-full grid grid-cols-1 md:grid-cols-2 gap-10 py-10 lg:py-10">
      <div class="w-full">
        <img src="../assets/about.svg" class="max-w-3xl mx-auto h-auto" alt="" />
      </div>
      <div class="w-full flex flex-col gap-10">
        <div class="flex gap-4 items-start">
          <img src="../assets/mission 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h3
              class="font-semibold tracking-normal text-left text-gray-900"
              style="font-size: 24px"
            >
              Our Mission
            </h3>
            <p
              class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal"
              style="font-size: 16px"
            >
              We are committed to impacting brands and businesses by enabling their
              software journeys through strategic consulting services using the best
              technologies.
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/future 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h3
              class="font-semibold tracking-normal text-left text-gray-900"
              style="font-size: 24px"
            >
              Our Vision
            </h3>
            <p
              class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal"
              style="font-size: 16px"
            >
              Our Vision is to connect businesses and customers using state of the art web
              technologies that will make our company the world’s premier software company
            </p>
          </div>
        </div>
      </div>
    </div>
    <div
      class="flex flex-col md:flex-row space-x-0 md:space-x-5 space-y-5 md:space-y-0 hidden"
    >
      <div class="w-full md:w-1/2 flex flex-row items-start space-x-5">
        <img src="../assets/mission 1.svg" class="w-8 md:w-14" alt="" />
        <div class="space-y-2">
          <h3
            class="font-semibold tracking-normal text-left text-gray-900"
            style="font-size: 24px"
          >
            Our Mission
          </h3>
          <p
            class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal"
            style="font-size: 16px"
          >
            We are committed to impacting brands and businesses by enabling their software
            journeys through strategic consulting services using the best technologies.
          </p>
        </div>
      </div>
      <div class="w-full md:w-1/2 flex flex-row items-start space-x-5">
        <img src="../assets/future 1.svg" class="w-8 md:w-14" alt="" />
        <div class="space-y-2">
          <h3
            class="font-semibold tracking-normal text-left text-gray-900"
            style="font-size: 24px"
          >
            Our Vision
          </h3>
          <p
            class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal"
            style="font-size: 16px"
          >
            Our Vision is to connect businesses and customers using state of the art web
            technologies that will make our company the world’s premier software company
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Team from "./team.vue";
export default {
  components: {
    Team,
  },
};
</script>
