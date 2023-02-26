<script setup>
import { RouterView } from "vue-router";

</script>

<template>
  <div class="app">
    <header>
      <div class="wrapper">
        <!-- <nav hidden>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
        </nav> -->
      </div>
    </header>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped>

</style>
