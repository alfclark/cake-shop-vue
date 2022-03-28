<template>
  <div class="cart">
    <div class="cart-wrapper">
      <section class="h-100 h-custom" style="background-color: #d2c9ff">
        <div class="container py-5 h-100">
          <div
            class="row d-flex justify-content-center align-items-center h-100"
          >
            <div class="col-12">
              <div
                class="card card-registration card-registration-2"
                style="border-radius: 15px"
              >
                <div class="card-body p-0">
                  <div class="row g-0">
                    <div class="col-lg-8">
                      <div class="p-5">
                        <div
                          class="d-flex justify-content-between align-items-center mb-5"
                        >
                          <h3 class="fw-bold mb-0 text-black">Shopping Cart</h3>
                          <h6 class="mb-0 text-muted">3 items</h6>
                        </div>
                        <hr class="my-4" />

                        <div
                          class="row mb-4 d-flex justify-content-between align-items-center"
                        >
                          <div class="col-md-2 col-lg-2 col-xl-2">
                            <img
                              src="https://cdn.pickuplimes.com/cache/e8/d2/e8d2767ce7ba58f8bf0ffb62b17415c8.jpg"
                              class="img-fluid rounded-3"
                              alt="Cotton T-shirt"
                            />
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-3">
                            <h6 class="text-muted">Cake</h6>
                            <h6 class="text-black mb-0">Chocolate Cake</h6>
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-2 d-flex">
                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepDown()"
                            >
                              <i class="fas fa-minus"></i>
                            </button>

                            <input
                              id="form1"
                              min="0"
                              name="quantity"
                              value="1"
                              type="number"
                              class="form-control form-control-sm"
                            />

                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepUp()"
                            >
                              <i class="fas fa-plus"></i>
                            </button>
                          </div>
                          <div class="col-md-3 col-lg-2 col-xl-2 offset-lg-1">
                            <h6 class="mb-0">$ 25.00</h6>
                          </div>
                          <div class="col-md-1 col-lg-1 col-xl-1 text-end">
                            <a href="#!" class="text-muted"
                              ><i class="fas fa-times"></i
                            ></a>
                          </div>
                        </div>

                        <hr class="my-4" />

                        <div
                          class="row mb-4 d-flex justify-content-between align-items-center"
                        >
                          <div class="col-md-2 col-lg-2 col-xl-2">
                            <img
                              src="https://www.onceuponachef.com/images/2017/12/cheesecake-1200x1393.jpg"
                              class="img-fluid rounded-3"
                              alt="Cotton T-shirt"
                            />
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-3">
                            <h6 class="text-muted">Cake</h6>
                            <h6 class="text-black mb-0">Cheesecake</h6>
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-2 d-flex">
                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepDown()"
                            >
                              <i class="fas fa-minus"></i>
                            </button>

                            <input
                              id="form1"
                              min="0"
                              name="quantity"
                              value="1"
                              type="number"
                              class="form-control form-control-sm"
                            />

                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepUp()"
                            >
                              <i class="fas fa-plus"></i>
                            </button>
                          </div>
                          <div class="col-md-3 col-lg-2 col-xl-2 offset-lg-1">
                            <h6 class="mb-0">$ 30.00</h6>
                          </div>
                          <div class="col-md-1 col-lg-1 col-xl-1 text-end">
                            <a href="#!" class="text-muted"
                              ><i class="fas fa-times"></i
                            ></a>
                          </div>
                        </div>

                        <hr class="my-4" />

                        <div
                          class="row mb-4 d-flex justify-content-between align-items-center"
                        >
                          <div class="col-md-2 col-lg-2 col-xl-2">
                            <img
                              src="https://www.onceuponachef.com/images/2012/11/Vanilla-Birthday-Cake-18.jpg"
                              class="img-fluid rounded-3"
                              alt="Cotton T-shirt"
                            />
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-3">
                            <h6 class="text-muted">Cake</h6>
                            <h6 class="text-black mb-0">
                              Birthday Vanilla Cake
                            </h6>
                          </div>
                          <div class="col-md-3 col-lg-3 col-xl-2 d-flex">
                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepDown()"
                            >
                              <i class="fas fa-minus"></i>
                            </button>

                            <input
                              id="form1"
                              min="0"
                              name="quantity"
                              value="1"
                              type="number"
                              class="form-control form-control-sm"
                            />

                            <button
                              class="btn btn-link px-2"
                              onclick="this.parentNode.querySelector('input[type=number]').stepUp()"
                            >
                              <i class="fas fa-plus"></i>
                            </button>
                          </div>
                          <div class="col-md-3 col-lg-2 col-xl-2 offset-lg-1">
                            <h6 class="mb-0">$ 42.00</h6>
                          </div>
                          <div class="col-md-1 col-lg-1 col-xl-1 text-end">
                            <a href="#!" class="text-muted"
                              ><i class="fas fa-times"></i
                            ></a>
                          </div>
                        </div>

                        <hr class="my-4" />

                        <div class="pt-5">
                          <h6 class="mb-0">
                            <a class="text-body"
                              ><i class="fas fa-long-arrow-alt-left me-2"></i
                              ><router-link to="/">Home</router-link></a
                            >
                          </h6>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-4 bg-grey">
                      <div class="p-5">
                        <h3 class="fw-bold mb-5 mt-2 pt-1">Summary</h3>
                        <hr class="my-4" />

                        <div class="d-flex justify-content-between mb-4">
                          <h5 class="text-uppercase">items 3</h5>
                          <h5>$ 97.00</h5>
                        </div>

                        <h5 class="text-uppercase mb-3">Shipping</h5>

                        <div class="mb-4 pb-2">
                          <select class="select">
                            <option value="1">Standard-Delivery- $5.00</option>
                            <option value="2">Next-day Delivery - $8.00</option>
                            <option value="3">
                              Same-day Delivery - $10.00
                            </option>
                          </select>
                        </div>

                        <h5 class="text-uppercase mb-3">Give code</h5>

                        <div class="mb-5">
                          <div class="form-outline">
                            <input
                              type="text"
                              id="form3Examplea2"
                              class="form-control form-control-lg"
                            />
                            <label class="form-label" for="form3Examplea2"
                              >Enter your code</label
                            >
                          </div>
                        </div>

                        <hr class="my-4" />

                        <div class="d-flex justify-content-between mb-5">
                          <h5 class="text-uppercase">Total price</h5>
                          <h5>$ 102.00</h5>
                        </div>

                        <button
                          type="button"
                          class="btn btn-block btn-lg"
                          data-mdb-ripple-color="dark"
                        >
                          Proceed to Payment
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
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
  height: 100%;
}
.p-5 .btn-block {
  background-color: #6242c1c9;
  color: white;
}
.p-5 .btn-block:hover {
  background-color: #434344;
  transition: 0.4s;
}
</style>
