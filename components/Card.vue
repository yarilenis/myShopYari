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

<style lang="scss" scoped>
  .card {
    &__image{
      width: 100%;
    }
    &__img {
      border-top-left-radius: 0.25rem;
      border-top-right-radius: 0.25rem;
      width: 100%;
    }
    &__description {
      text-align: left;
      padding: 10px
    }
  }
  .btn-add-cart{
    position: absolute;
    right: 0;
    bottom: 0;
    .fa-circle{
      font-size: 35px;
    }
    .fa-cart-plus{
      position: absolute;
      top: 30%;
      color: white;
      left: 30%;
      font-size: 20px;
    }
  }
</style>
