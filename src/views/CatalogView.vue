<template>
  <div class="catalog">
    <h1>This is a catalog page</h1>
  </div>
  <FooterComp />
</template>

<script>
// @ is an alias to /src
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "CatalogView",
  components: {
    FooterComp,
  },
};
</script>

<style scoped>
.catalog {
  height: 90vh;
}
</style>
