<script setup>
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
  isActive: {
    type: Boolean,
    required: false,
    default: false,
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
    <a
      class="nav-link"
      :class="{ active: isActive, disabled: isDisabled }"
      aria-current="page"
      :href="url"
      :disabled="isDisabled"
      :aria-disabled="isDisabled"
      >{{ text }}</a
    >
  </li>
</template>
