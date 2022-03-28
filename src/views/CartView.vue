<template>
  <div class="cart">
    <h1>This is the cart page</h1>
  </div>
  <FooterComp />
</template>

<script>
// @ is an alias to /src
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "CartView",
  components: {
    FooterComp,
  },
};
</script>

<style scoped>
.cart {
  height: 90vh;
}
</style>
