<template>
  <NavBar />

  <div class="container is-max-desktop px-2 py-4">
    <RouterView />
  </div>
</template>

<script setup>
/*
  imports
*/
import 'bulma/css/bulma.css'
import NavBar from '@/components/Layout/NavBar.vue'
</script>

<style>

</style>