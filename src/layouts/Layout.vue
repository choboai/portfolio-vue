<script setup>
import Nav from '../components/Nav.vue';
import Footer from '../components/Footer.vue';
</script>

<template>
  <div class="d-flex flex-column h-100">
    <header>
      <Nav />
    </header>

    <main class="flex-shrink-0 pb-5">
      <div class="container">
        <slot />
      </div>
    </main>

    <Footer />
  </div>
</template>
