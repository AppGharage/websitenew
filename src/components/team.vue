<template>
  <div class="">
    <div class="mx-auto grid gap-y-20 gap-x-2 xl:grid-cols-3">
      <div class="max-w-2xl lg:mr-8">
        <h2 class="text-3xl font-semibold tracking-tight text-gray-900 sm:text-4xl">Meet our leadership</h2>
        <p class="mt-4 text-lg leading-8 text-gray-600">
          Making a positive difference has always been at the heart of our leaders values and motivation.
        </p>
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
              <div>{{ member.social }}</div>
            </div>
          </div>
        </li>
      </ul>
    </div>
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
          bio: "Software Engineer, Talent Manager and Community Builder.",
          img: "https://miro.medium.com/max/2400/1*5bQpLyeimQ4H1ihYXpE3Jw.jpeg",
        },
        {
          name: "Roberta Mawunyo Akoto",
          position: "Co-founder & Product Manager",
          bio: "Product Manager, Software Engineer, Writer, Community Builder and Volunteer.",
          img: "https://avatars.githubusercontent.com/u/33154097?v=4",
        },
      ],
    };
  },
};
</script>
