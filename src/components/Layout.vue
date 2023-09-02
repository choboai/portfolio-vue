<script setup>
import Nav from './Nav.vue';
import Footer from './Footer.vue';
</script>

<template>
  <div class="d-flex flex-column h-100">
    <header>
      <Nav />
    </header>

    <main class="flex-shrink-0 py-5">
      <div class="container">
        <slot name="title" />
        <slot name="content" />
      </div>
    </main>

    <Footer />
  </div>
</template>

<style>
#app {
  height: 100vh;
}
</style>
