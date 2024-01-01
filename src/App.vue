<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <h1 class="bg-black">check</h1>
      <RouterLink to="/">Home</RouterLink>
    </div>
  </header>

  <RouterView />
</template>
