<template>
  <div class="col-12 col-sm-6 col-md-4 col-lg-3 mt-3">
    <div class="card">
      <div class="card__image">
        <img
          src="https://picsum.photos/200/200/?random"
          alt="imagen producto"
          class="card__img img-fluid"
        />
      </div>
      <div class="card__description">
        <p class="card__title">Producto 1</p>
        <div>
          <span class="card__price">S/ 10.00</span>
          <button type="button" class="btn btn-add-cart">
            <i class="fa fa-circle"></i>
            <i class="fa fa-cart-plus"></i>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  asyncData() {
    return {
      name: "Yari Yuri"
    }
  },
  components: {
    Card
  },
  methods: {
    addProduct() {

    }
  }
}
</script>
