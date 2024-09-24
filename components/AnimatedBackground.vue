<template>
	<div class="animated-background" />
</template>

<script setup>
// import { useColorMode } from '@vueuse/core';

// const colorMode = useColorMode();
</script>

  <style scoped>
  .animated-background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
  }

  .light .animated-background {
    background: radial-gradient(ellipse at bottom, #f0f4f8 0%, #d0e1f9 100%);
  }

  .dark .animated-background {
    background: radial-gradient(ellipse at bottom, #0d1d31 0%, #0c0d13 100%);
  }

  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  </style>
