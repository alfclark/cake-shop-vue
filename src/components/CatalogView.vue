<template>
  <div id="catalog" class="catalog">
    <h3 class="catalog-title">Or buy our premade designs</h3>
    <div class="catalog-cards">
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
      <div class="card">
        <div class="title">
          <h3>Chocolate Cake</h3>
        </div>
        <img
          src="https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/0A475B34-4E78-40D8-9F30-46223B7D77E7/Derivates/E55C7EA4-0E60-403F-B5DC-75EA358197BD.jpg"
          alt=""
        />
        <p class="desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
          aliquam temporibus beatae aliquid quod amet quisquam laudantium
          commodi impedit voluptate.
        </p>
        <h3>$25.49</h3>
        <button>Add to Cart</button>
      </div>
    </div>
    <router-link to="/catalog">
      <button class="full-catalog">See full catalog</button>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.catalog {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  margin: 1rem 0 2rem 0;
  background-color: #dacab5;
  padding: 1rem 0;
}
.catalog-title {
  color: black;
  margin: 1rem;
  font-size: 2rem;
}
.catalog-cards {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
  margin: 1rem;
}
.card {
  width: 20vw;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 1rem;
  border-radius: 1rem;
}
.card h3 {
  font-size: 1.5rem;
}
.card img {
  width: 100%;
}
.card .desc {
  margin-top: 0.5rem;
  font-size: 0.8rem;
}
.card button {
  border: none;
  background-color: var(--brown);
  padding: 0.5rem 1rem;
  border-radius: 2rem;
  color: white;
}
.card button:hover {
  background-color: var(--grey);
  transition: 0.4s;
}
.full-catalog {
  border: none;
  background-color: var(--brown);
  color: white;
  padding: 1rem 2rem;
  border-radius: 3rem;
}
.card button:hover,
.full-catalog:hover {
  background-color: var(--grey);
  transition: 0.4s;
}
@media screen and (max-width: 800px) {
  .card {
    width: 90%;
  }
}
</style>
