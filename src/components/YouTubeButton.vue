<template>
  <a 
    :href="href"
    target="_blank"
    class="
      px-3
      py-2
      rounded
      border-2
      border-red-500
      text-red-500
      hover:bg-red-500
      hover:text-white
      hover:border-red-700
      font-semibold"
  >
    <slot></slot>
  </a>
</template>

<script setup>
const props = defineProps({
  href: String
})
</script>