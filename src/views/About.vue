<script></script>

<template>
  <div class="about-wrapper">
    <div class="container left">
      <h3 class="rose-font" v-motion-slide-left>ROSE</h3>
      <h3 class="par-font">par</h3>
      <h3 class="choix-font">Choix</h3>
      <div class="pink-circle"></div>
    </div>
    <div class="right">
      <h2>Croustine</h2>
    </div>
  </div>
</template>

<style>
.about-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  width: 70%;
  margin: 500px auto 0;
  margin-top: 70px;
}

.left {
  position: relative;
  background-color: #f5f5f5;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  border-radius: 15px;
  width: 40%;
  height: 70vh;
  overflow: hidden;
}

.right {
  width: 45%;
  height: 70vh;
}

.pink-circle {
  position: absolute;
  height: 230px;
  width: 230px;
  top: 60%;
  left: 40%;
  border-radius: 50%;
  background-color: var(--pink);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.rose-font {
  position: absolute;
  top: 100px;
  right: 100px;
  color: var(--grey);
  font-family: "Gloock", sans-serif;
  font-size: 8rem;
  letter-spacing: 10px;
}

.par-font {
  position: absolute;
  top: 250px;
  right: 100px;
  font-family: "Montserrat", sans-serif;
  font-style: italic;
  font-size: 3rem;
  letter-spacing: 10px;
  color: #bbb;
}

.choix-font {
  position: absolute;
  top: 350px;
  font-family: "Roboto", sans-serif;
  font-style: italic;
  font-weight: 700;
  font-size: 9rem;
  letter-spacing: 10px;
  color: #999;
  z-index: 1;
}
</style>
