<template>
  <div class="col-12 col-sm-6 col-md-3 mt-3">
    <div class="card">
      <div class="card__image">
        <img
          src="https://picsum.photos/200/200/?random"
          alt="imagen producto"
          class="card__img image-fluid"
        />
      </div>
      <div class="card__description">
        <p class="card__title">Producto 1</p>
        <div>
          <span class="card__price">S/ 10.00</span>
          <button type="button" class="btn">
            <i class="fa fa-circle"></i>
            <i class="fa fa-cart-plus"></i>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .card__image {
    width: 100%;
  }
  .card__img {
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem;
  }
  .card__description {
    text-align: left;
    padding: 10px
  }

</style>
