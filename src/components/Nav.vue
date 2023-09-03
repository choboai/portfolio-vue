<script setup>
import NavLink from './NavLink.vue';
import { RouterLink } from 'vue-router';
</script>

<template>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <div class="container-fluid">
      <RouterLink class="navbar-brand" to="/">Mon site</RouterLink>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarCollapse"
        aria-controls="navbarCollapse"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav me-auto mb-2 mb-md-0">
          <NavLink url="/" text="Accueil" />
          <NavLink url="/about" text="À propos" />
        </ul>
      </div>
    </div>
  </nav>
</template>
