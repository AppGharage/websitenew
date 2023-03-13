<template>
  <div>
    <h2 class="font-semibold tracking-normal text-center text-gray-900 text-5xl mb-4">Meet our team</h2>
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
          bio:
            "Baffour has over 7 years of experience as a self taught software engineer and 2 years experience as talent manager. He is a community activist in Ghana.",
          img: "https://miro.medium.com/max/2400/1*5bQpLyeimQ4H1ihYXpE3Jw.jpeg",
        },
        {
          name: "Roberta Mawunyo Akoto",
          position: "Co-founder & Product Manager",
          bio:
            "Roberta has close to 6 years of experience as a self taught software engineer and 4 years of experience working as a product manager at AppGharage. She is a tech enthusiast and community activist. She was also the co-lead of Meta Developer Circle, Accra from 2018 to 2020. ",
          img: "https://avatars.githubusercontent.com/u/33154097?v=4",
        },
      ],
    };
  },
};
</script>
