<template>
  <div>
    <div class="bg-white py-24 sm:py-24">
      <div class="mx-auto grid max-w-7xl gap-y-20 gap-x-8 px-6 lg:px-8 xl:grid-cols-3">
        <div class="max-w-2xl">
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Meet our leadership</h2>
          <p class="mt-6 text-lg leading-8 text-gray-600">Libero fames augue nisl porttitor nisi, quis. Id ac elit odio vitae elementum enim vitae ullamcorper suspendisse.</p>
        </div>
        <ul role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">
          <li v-for="member in team" :key="member">
            <div class="flex items-center gap-x-6">
              <img class="h-16 w-16 rounded-full" :src="member.img" alt="">
              <div>
                <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">{{ member.name }}</h3>
                <p class="text-sm font-semibold leading-6 text-blue-700">{{ member.position }}</p>
                <p
                  class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal mt-4"
                >
                  {{ member.bio }}
                </p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>


    <!-- <h2 class="font-semibold tracking-normal text-center text-gray-900 text-5xl mb-4">Meet our team</h2>
    <div class="w-full grid grid-cols-1 lg:grid-cols-2 gap-10 py-10">
      <div class="w-full flex gap-4" v-for="member in team" :key="member">
        <div class="w-32 h-32 overflow-hidden rounded-lg">
          <img
            :src="member.img"
            class="w-full h-full object-center object-cover"
            alt="name"
          />
        </div>
        <div class="flex-1">
          <p
            class="font-semibold tracking-normal text-left text-gray-900"
            style="font-size: 24px"
          >
            {{ member.name }}
          </p>
          <p class="text-lg font-semibold text-red-600 leading-7">
            {{ member.position }}
          </p>
          <p
            class="font-normal tracking-normal text-base text-left text-gray-500 leading-normal mt-4"
          >
            {{ member.bio }}
          </p>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      team: [
        {
          name: "Baffour Adu Boampong",
          position: "Co-founder & CEO",
          bio:
            "Software Engineer, Talent Manager and Community Builder",
          img: "https://miro.medium.com/max/2400/1*5bQpLyeimQ4H1ihYXpE3Jw.jpeg",
        },
        {
          name: "Roberta Mawunyo Akoto",
          position: "Co-founder & Product Manager",
          bio:
            "Product Manager, Software Engineer, Writer Community Builder and Volunteer ",
          img: "https://avatars.githubusercontent.com/u/33154097?v=4",
        },
      ],
    };
  },
};
</script>
