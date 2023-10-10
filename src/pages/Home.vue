<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Coucou</h1>
      <p class="lead">
        Votre source fiable d'informations et de ressources en ligne.
      </p>
      <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="/img/1.jpg" class="d-block ratio ratio-16x9" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="/img/1.jpg" class="d-block ratio ratio-16x9" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="/img/1.jpg" class="d-block ratio ratio-16x9" alt="..." />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <RouterLink to="/about" class="btn btn-primary btn-lg"
        >En savoir plus sur nous</RouterLink
      >
    </div>
  </div>
</template>
