<template>
  <div class="build">
    <h1>This is the build page</h1>
  </div>
  <FooterComp />
</template>

<script>
// @ is an alias to /src
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "BuildView",
  components: {
    FooterComp,
  },
};
</script>

<style scoped>
.build {
  height: 90vh;
}
</style>
