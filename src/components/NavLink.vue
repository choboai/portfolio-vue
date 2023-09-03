<script setup>
import { RouterLink } from 'vue-router';
defineProps({
  url: {
    type: String,
    required: false,
    default: '',
  },
  text: {
    type: String,
    required: true,
  },
  isDisabled: {
    type: Boolean,
    required: false,
    default: false,
  },
});
</script>

<template>
  <li class="nav-item">
    <RouterLink
      class="nav-link"
      :class="{ disabled: isDisabled }"
      activeClass="active"
      aria-current="page"
      :to="url"
      :disabled="isDisabled"
      :aria-disabled="isDisabled"
      >{{ text }}</RouterLink
    >
  </li>
</template>
