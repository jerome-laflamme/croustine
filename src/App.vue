<script setup>
import { RouterView } from "vue-router";

</script>

<template>
  <div class="app">
    <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/about">à propos</RouterLink>
          <RouterLink to="/about">portfolio</RouterLink>
        </nav>
      </div>
    </header>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: right;
  align-items: center;
  width: 100%;
  height: 100%;
  padding: 50px;
}

a {
  font-size: 1rem;
  font-weight: 700;
  color: var(--grey);
  text-decoration: none;
  z-index: 3;
  margin-left: 50px;
}
</style>
