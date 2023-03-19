<template>
  <div class="max-w-screen-xl mx-auto px-5 md:px-10 xl:px-0 space-y-16 md:space-y-20">
    <div class="w-full flex flex-col-reverse lg:flex-row md:mt-20">
      <div class="w-full lg:w-3/5 space-y-5 md:my-auto flex flex-col">
          <h2 class="text-4xl lg:text-5xl font-light lg:text-left md:text-center font-medium leading-normal lg:leading-normal text-gray-900">
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
      <div class="w-full lg:w-2/5 md:flex">
        <img src="../assets/worldclass.gif" class="w-full hidden lg:block" alt="" />
      </div>
    </div>

    <!-- <div class="w-full grid grid-cols-1 md:grid-cols-2 gap-10 py-10 lg:py-10">
      <div class="w-full">
        <img src="../assets/about.gif" alt="" class="max-w-3xl w-96 items-center mt-10 hidden lg:block">
      </div>
      <div class="w-full flex flex-col gap-10">
        <div class="flex gap-4 items-start">
          <img src="../assets/overview.png" alt="" class="w-8 md:w-14">
          <div class="space-y-2">
              <h2 class="font-semibold tracking-normal text-left text-gray-900 text-2xl">
                Overview
              </h2>
              <p class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal">
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
          <img src="../assets/story.png" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2 class="font-semibold tracking-normal text-left text-gray-900 text-2xl">
              Our Story
            </h2>
            <p class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal">
              AppGharage was founded in 2018 with a team of tech porfessionals and enthusiasts. Through AppGharage, Epay was birth which was a service 
              provider and operated for 2 years succesfully with over 100 clients within months of operation.
              Fast forward to building in-house ideas, we launched <a href="https://jolinow.com/" class="text-blue-700 font-semibold">Jolinow.</a>
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/vision.png" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2 class="font-semibold tracking-normal text-left text-gray-900 text-2xl">
              Our Vision
            </h2>
            <p class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal">
              Our Vision is to be the World's best Software development and consulting firm helping businesses achieve their goals
              and connecting the world to state of the art web technologies.
            </p>
          </div>
        </div>
        <div class="flex gap-4 items-start">
          <img src="../assets/values.png" class="w-8 md:w-14" alt="" />
          <div class="space-y-2">
            <h2 class="font-semibold tracking-normal text-left text-gray-900 text-2xl">
              Our Values
            </h2>
            <p class="font-normal tracking-normal text-medium text-left text-gray-500 leading-normal">
              We are group of individuals with <span class="font-semibold text-lg text-blue-700">integrity</span> from 
              <span class="font-semibold text-lg text-blue-700">diverse</span> backgrounds, who take <span class="font-semibold text-lg text-blue-700">
              responsibility</span> and <span class="font-semibold text-lg text-blue-700">innovation</span> 
              at heart to deliver quality work to our clients.
            </p>
          </div>
        </div>
      </div>
    </div> -->

    <div class="relative z-20 sm:z-auto xl:px-0">
      <div class="mx-auto pb-16">
        <div class="relative mx-auto grid max-w-[40rem] grid-cols-1 gap-4 lg:max-w-none lg:grid-cols-2">
          <div class="flex mt-2">
            <img src="../assets/overview.svg" alt="" class="pt-2 h-14 w-14 mr-3">
            <div class="leading-6">
              <h2 class="font-semibold text-2xl mb-2">
                Overview
              </h2>
              <p class="text-lg text-gray-600">
                AppGharage is a Software Development and Consultancy firm in Ghana that partners with 
                small to large organizations to help them increase efficiency and productivity.
                <br><br>
                We accomplish this is by meeting with our clients, understanding their current operating environment,
                where they are now and what they want to archieve, then creating the roadmap and buidling simple 
                solutions to make them get there.
              </p>
            </div>
          </div>
          <div class="flex mt-4">
              <img src="../assets/story.svg" alt="" class="pt-2 h-14 w-14 mr-3">
            <div class="leading-6">
              <h2 class="font-semibold text-2xl mb-2">
                  Our Story
              </h2>
              <p class="text-lg text-gray-600">
                AppGharage was founded in 2018 with a team of tech porfessionals and enthusiasts. Through AppGharage, Epay was birth which was a payment service 
                provider and operated for 2 years succesfully with over 100 clients and $200,000 in process value within 14 months of operation.
                Fast forward to building in-house ideas, we have launched <a href="https://jolinow.com/" class="text-blue-700 font-semibold">Jolinow.</a> 
              </p>
            </div>
          </div>
          <div class="flex mt-4">
            <img src="../assets/vision.svg" alt="" class="pt-2 h-14 w-14 mr-3">
            <div class="leading-6">
              <h2 class="font-semibold text-2xl mb-2">
                  Our Vision
              </h2>
              <p class="text-lg text-gray-600">
                Our Vision is to be Africa's best Software development and consulting firm helping businesses achieve their goals
                and connecting the world to state of the art web technologies.
              </p>
            </div>
          </div>
          <div class="flex mt-4">
            <img src="../assets/values.svg" alt="" class="pt-2 h-14 w-14 mr-3">
            <div class="leading-6">
              <h2 class="font-semibold text-2xl mb-2">
                Our Values
              </h2>
              <p class="text-lg text-gray-600">
                We are group of individuals with <span class="font-semibold text-lg text-blue-700">integrity</span> from 
                <span class="font-semibold text-lg text-blue-700">diverse</span> backgrounds, who take <span class="font-semibold text-lg text-blue-700">
                responsibility</span> and <span class="font-semibold text-lg text-blue-700">innovation</span> 
                at heart to deliver quality work to our clients.
              </p>
            </div>
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
