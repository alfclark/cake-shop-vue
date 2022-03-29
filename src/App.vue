<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <a class="navbar-brand d-flex justify-content-center align-items-center">
        <router-link class="router" to="/">
          <img class="logo" src="@/assets/logo.png" alt="" />
          <h3 class="brand-name">SugarPanda</h3>
        </router-link>
      </a>
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
            <a class="nav-link"
              ><router-link to="/catalog">Catalog</router-link></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link"
              ><router-link to="/build">Build Your Cake</router-link></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link"><router-link to="/about">About</router-link></a>
          </li>
          <li class="nav-item">
            <a class="nav-link"
              ><router-link to="cart"
                ><i class="fa-solid fa-cart-shopping"></i></router-link
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
  --black: #080808;
  --brown: #8f7865;
  --beige: #b8a3f8bb;
  --yellow: #f2b233;
  --grey: #66523e;
}
#app {
  background-color: var(--black);
}
body {
  font-family: "Poppins", sans-serif;
}
.navbar {
  padding: 0 3rem 0 3rem;
  height: 10vh;
  z-index: 3;
}
.router {
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo {
  width: 4rem;
}
.navbar-collapse {
  padding: 1rem;
}
.navbar-toggler {
  background-color: var(--brown);
}
.brand-name {
  color: white;
  font-size: 1rem;
}
a {
  text-decoration: none;
  color: white;
  font-weight: 500;
  font-size: 1;
}
a:hover {
  color: var(--brown);
  transition: 0.4s;
}
</style>
