<template>
  <div class="hello">
    <div class="hello-image"></div>
    <div class="hello-content">
      <h1>Build the Cake of your dreams</h1>
      <p>Use our new tool to build your own cake.</p>
      <button class="build-btn">
        <router-link class="btn-text" to="/build">Build Cake</router-link>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingScreen",
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
  justify-content: center;
  align-items: center;
  width: 100%;
  padding: 0;
  margin: 0;
}
.hello-image {
  height: 100%;
  width: 50%;
  background-image: url("https://images.unsplash.com/photo-1512223792601-592a9809eed4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=652&q=80");
  opacity: 65%;
  background-color: #cccccc;
}
.hello-content {
  widows: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding: 1rem;
}
.hello h1 {
  font-family: Junitta;
  font-size: 6rem;
  text-align: center;
  color: white;
}
.hello p {
  font-size: 1.5rem;
  text-align: center;
  color: white;
}
.build-btn {
  background-color: var(--brown);
  font-size: 1.5rem;
  border: none;
  padding: 0.5rem 1.5rem;
  cursor: pointer;
  border-radius: 2rem;
}
.btn-text {
  color: white;
}

.build-btn:hover {
  background-color: #000000;
  transition: 0.6s;
  border: solid 1px white;
}
@media screen and (max-width: 900px) {
  .hello-image {
    display: none;
  }
}
</style>
