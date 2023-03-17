<template>
  <div class="home">
    <navbar
      class="nav-fix filter"
      :class="[isscroll ? 'bg-white drop-shadow ' : 'bg-transparent drop-shadow-none']"
    />
    <projects class="mt-10 mb-10" />
    <Cta ctaimg="productsv.svg" />
    <foooter />
  </div>
</template>

<script>
// @ is an alias to /src
import projects from "../components/projects.vue";
import Cta from "../components/callToAction.vue";
import navbar from "../components/navbar.vue";
import foooter from "../components/foooter.vue";

export default {
  name: "Projects",
  components: {
    projects,
    Cta,
    navbar,
    foooter,
  },
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
    //navbar scroll
    window.onscroll = () => {
      //console.log(window.scrollY)
      if (window.scrollY > 50) {
        this.isscroll = true;
      } else {
        this.isscroll = false;
      }
    };
  },
};
</script>
