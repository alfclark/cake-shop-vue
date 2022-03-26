<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <a class="navbar-brand"
        ><img class="logo" src="@/assets/logo.png" alt=""
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link"><router-link to="/">Home</router-link></a>
          </li>
          <li class="nav-item">
            <a class="nav-link"><router-link to="/about">About</router-link></a>
          </li>
          <li class="nav-item">
            <a class="nav-link"
              ><router-link to="/about">Catalog</router-link></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link"
              ><router-link to="/about">Build Your Cake</router-link></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link"
              ><router-link to="/about"
                ><router-link to="/about"
                  ><i
                    class="fa-solid fa-cart-shopping"
                  ></i></router-link></router-link
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&display=swap");
:root {
  --purple: #6242c1bb;
  --beige: #b8a3f8bb;
  --yellow: #f2b233;
}
#app {
  background-color: var(--beige);
}
body {
  font-family: "Poppins", sans-serif;
}
.navbar {
  padding: 0 3rem 0 3rem;
  height: 10vh;
}
.logo {
  width: 4rem;
}

a {
  text-decoration: none;
  color: black;
  font-weight: 500;
  font-size: 1;
}
a:hover {
  color: var(--purple);
  transition: 0.4s;
}
</style>
