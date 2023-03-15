<template>
  <div class="max-w-screen-xl mx-auto px-5 md:px-10 xl:px-0 space-y-16 md:space-y-24">
    <div class="w-full flex flex-col md:flex-row md:mt-20">
      <div class="space-y-5 my-0 md:my-auto flex flex-col">
          <h2 class="text-4xl font-light lg:text-left md:text-center font-medium leading-normal lg:leading-normal text-gray-900">
            We are a technology company creating <span class="text-blue-600">world-class</span> products.
          </h2>
          <div class="h-20 pt-10">
              <router-link
                to="/contact"
                class="px-5 py-3 text-white text-lg font-medium bg-blue-700 rounded-br-2xl"
                >Let's Talk !</router-link
              >
          </div>
          <!-- <h1
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
          </p> -->
      </div>
      <div class="w-full md:w-1/2 pl-0 lg:pl-20 md:flex">
        <img src="../assets/amico.svg" class="h-full hidden lg:block " alt="" />
      </div>
    </div>
    <!-- <div class="mx-auto max-w-xl p-10 px-0 text-center">
      <h2 class="text-4xl font-bold leading-tight text-black">Our Story</h2>
      <p class="mt-3 text-md text-gray-600">
        At AppGharage, customer satisfaction is always our priority. We provide softwares for 
        clients focusing on creating products the right way.
      </p>
    </div> -->

    <div class="w-full grid grid-cols-1 md:grid-cols-2 gap-10 py-10 lg:py-10">
     
      <div class="w-full flex flex-col gap-10">
        <div class="flex gap-4 items-start">
          <img src="../assets/future 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2
              class="font-semibold tracking-normal text-left text-gray-900 text-2xl"
            >
              Overview
            </h2>
            <p
              class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal"
            >
              AppGharage is a Software Development and Consultancy firm in Ghana that partners with 
              small to large organizations to help them increase efficiency and productivity.
              <br><br>
              We accomplish this is by meeting with our clients, understand their current operating environment,
              where they are now and where they want to archieve, then creating the roadmap and buidling simple 
              solutions to make them get there.
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/mission 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2
              class="font-semibold tracking-normal text-left text-gray-900 text-2xl"
            >
              Our Story
            </h2>
            <p
              class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal"
            >
              AppGharage was founded in 2018 with a team of tech porfessionals and enthusiasts. Through AppGharage, Epay was birth which was a service 
              provider and operated for 2 years succesfully with over 100 clients within months of operation.
              Fast forward to building in-house ideas, we launched <a href="https://jolinow.com/" class="text-blue-700">Jolinow.</a>
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/future 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2
              class="font-semibold tracking-normal text-left text-gray-900 text-2xl"
            >
              Our Vision
            </h2>
            <p
              class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal"
            >
              Our Vision is to be the World's best Software development and consulting firm to help businesses achieve their goals
              by using state of the art web technologies.
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/future 1.svg" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2
              class="font-semibold tracking-normal text-left text-gray-900 text-2xl"
            >
              Our Values
            </h2>
            <!-- <div class="pl-4">
              <ul class="list-disc list-inside">
                <li>Work Hard, Play Hard</li>
                <li>Keep it simple</li>
                <li>Build trust with transparency and security</li>
              </ul>
            </div> -->
            <p
              class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal"
            >
              We are group of individuals with <span class="font-semibold text-lg text-blue-700">integrity</span> from <span class="font-semibold text-lg text-blue-700">diverse</span> 
              backgrounds, who take <span class="font-semibold text-lg text-blue-700">responsibility</span> and <span class="font-semibold text-lg text-blue-700">innovation</span> 
              at heart to deliver quality work to our clients.
            </p>
          </div>
        </div>
      </div>
    </div>
    <Team />
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
