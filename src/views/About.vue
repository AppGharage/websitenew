<template>
  <div class="about">
    <navbar
      class="nav-fix filter"
      :class="[isscroll ? 'bg-white drop-shadow ' : 'bg-transparent drop-shadow-none']"
    />
    <about class="mt-10 mb-24" />
    <cta ctaimg="aboutsv.svg" />
    <foooter />
  </div>
</template>

<script>
import about from "../components/about.vue";
import cta from "../components/callToAction.vue";
import navbar from "../components/navbar.vue";
import foooter from "../components/foooter.vue";

export default {
  components: { about, cta, navbar, foooter },
  data() {
    return {
      isscroll: false,
    };
  },

  created() {
    if ("scrollRestoration" in history) {
      history.scrollRestoration = "manual";
    }
    // This is needed if the user scrolls down during page load and you want to make sure the page is scrolled to the top once it's fully loaded. This has Cross-browser support.
    window.scrollTo(0, 0);
    //navbar scrolling
    window.onscroll = () => {
      if (window.scrollY > 50) {
        this.isscroll = true;
      } else {
        this.isscroll = false;
      }
    };
  },
};
</script>
