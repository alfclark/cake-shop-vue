<template>
  <div class="home">
    <LandingScreen />
    <FooterComp />
  </div>
</template>

<script>
// @ is an alias to /src
import LandingScreen from "@/components/LandingScreen.vue";
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "HomeView",
  components: {
    LandingScreen,
    FooterComp,
  },
};
</script>
