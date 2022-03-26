<template>
  <div class="hello">
    <h1>Build the Cake of your dreams</h1>
    <p>Use our new tool to build your own cake.</p>
    <button class="build-btn">
      <router-link class="btn-text" to="/about">Build Cake</router-link>
    </button>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@font-face {
  font-family: Junitta;
  src: url("@/assets/Junitta-BW55G.otf");
}
.hello {
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
.hello h1 {
  font-family: Junitta;
  font-size: 6rem;
  text-align: center;
}
.hello p {
  font-size: 1.5rem;
}
.build-btn {
  background-color: var(--purple);
  font-size: 1.5rem;
  border: none;
  color: var(--beige);
  padding: 0.5rem 1.5rem;
  cursor: pointer;
  border-radius: 2rem;
}
.btn-text {
  color: white;
}

.build-btn:hover {
  color: var(--beige);
  background-color: #000000;
  transition: 0.6s;
}
@media screen and (max-width: 450px) {
  .hello h1 {
    font-size: 3rem;
  }
  .build-btn {
    font-size: 1rem;
  }
  .build-title {
    font-size: 3rem;
  }
  .showcase {
    align-items: center;
  }
}
</style>
