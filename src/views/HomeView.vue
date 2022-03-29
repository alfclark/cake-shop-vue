<template>
  <div class="home">
    <LandingScreen />
    <CatalogView />
    <FooterComp />
  </div>
</template>

<script>
// @ is an alias to /src
import LandingScreen from "@/components/LandingScreen.vue";
import FooterComp from "@/components/FooterComp.vue";
import CatalogView from "@/components/CatalogView.vue";

export default {
  name: "HomeView",
  components: {
    LandingScreen,
    FooterComp,
    CatalogView,
  },
};
</script>
