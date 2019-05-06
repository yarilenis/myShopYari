<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <nuxt-link to="/" class="">
        <i class="fas fa-om"></i>
        Yari
      </nuxt-link>
      <ul class="navbar-nav ml-auto flex-row">
        <li class="nav-item px-2 active">
          <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Tienda</a>
        </li>
        <li class="nav-item px-2">
          <a class="nav-link" href="#">Contacto</a>
        </li>
        <li class="nav-item px-2">
          <i class="fas fa-shopping-cart nav-cart"></i>
          <div class="nav-cart__item">
            <span class="nav-cart__item-number">1</span>
          </div>
        </li>
      </ul>
    </nav>
    <div class="container">
      <nuxt/>
    </div>
    <div class="container">
      <div class="footer">

      </div>
    </div>
  </div>
</template>
