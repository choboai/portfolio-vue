<script setup>
import Layout from "../layouts/Layout.vue";
</script>

<template>
  <Layout>
    <h2>Projets</h2>
    <div id="projects" class="d-flex justify-content-evenly flex-wrap">
      <div class="col-12 col-md-5 col-lg-3 col-xl-2 card mb-4">
        <div
          class="img-background"
          style="background-image: url('/img/1.jpg')"
        ></div>
        <div class="card-body">
          <h5 class="card-title">Projet 1</h5>
          <p class="card-text">Petit texte explicatif!</p>
          <a href="#" class="btn btn-primary">Voir le projet</a>
        </div>
      </div>

      <div class="col-12 col-md-5 col-lg-3 col-xl-2 card mb-4">
        <div
          class="img-background"
          style="
            background-image: url('/img/tortue.jpg');
            background-position: left;
          "
        ></div>
        <div class="card-body">
          <h5 class="card-title">Projet 2</h5>
          <p class="card-text">Petit texte explicatif!</p>
          <a href="#" class="btn btn-primary">Voir le projet</a>
        </div>
      </div>

      <div class="col-12 col-md-5 col-lg-3 col-xl-2 card mb-4">
        <div
          class="img-background"
          style="background-image: url('/img/1.jpg')"
        ></div>
        <div class="card-body">
          <h5 class="card-title">Projet 1</h5>
          <p class="card-text">Petit texte explicatif!</p>
          <a href="#" class="btn btn-primary">Voir le projet</a>
        </div>
      </div>

      <div class="col-12 col-md-5 col-xl-3 col-xxxl-2 card mb-4">
        <div
          class="img-background"
          style="background-image: url('/img/1.jpg')"
        ></div>
        <div class="card-body">
          <h5 class="card-title">Projet 2</h5>
          <p class="card-text">Petit texte explicatif!</p>
          <a href="#" class="btn btn-primary">Voir le projet</a>
        </div>
      </div>
    </div>
  </Layout>
</template>
