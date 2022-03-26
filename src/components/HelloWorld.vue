<template>
  <div class="hello">
    <div class="hello-content">
      <h1>Build the Cake of your dreams</h1>
      <p>Use our new tool to build your own cake.</p>
      <button class="build-btn">
        <router-link class="btn-text" to="/about">Build Cake</router-link>
      </button>
    </div>
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
  background-image: url(https://www.pngplay.com/wp-content/uploads/2/Cake-PNG-HD-Quality.png);
  background-repeat: no-repeat;
  background-size: cover;
}
.hello-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  background-color: rgba(255, 255, 255, 0.801);
  border-radius: 1rem;
  padding: 1rem;
}
.hello h1 {
  font-family: Junitta;
  font-size: 6rem;
  text-align: center;
}
.hello p {
  font-size: 1.5rem;
  text-align: center;
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
  .hello p {
    font-size: 1rem;
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
