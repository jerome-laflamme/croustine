<script setup>

</script>

<template>
  <main>
    <div class="background">
      <h1 class="rose">ROSE</h1>
      <h1 class="par">PAR</h1> 
      <h1 class="choix">CHOIX</h1>
    </div>
    <div class="wrapper">
      <p class="welcome">bienvenu chez croustine</p>
    </div>
    
  </main>
</template>

<style>

h1 {
  position: fixed;
  top: -5%;
  color: var(--pink);
  font-size: 135vh;
  letter-spacing: -0.08em;
  line-height: 0.8;
  width: 100vw;
}

.rose {
  animation: Rose 20s linear infinite;
}

.par {
  animation: Par 20s linear infinite;
  color: #BBB;
}

.choix {
  animation: Choix 20s linear infinite;
  color: #999;
}


.welcome {
  font-size: 1rem;
  font-weight: 700;
  width: 150px;
  height: 150px;
  text-align: right;
  z-index: -2;
  background-color: rgba(0, 0, 0, 0.1);
  border-radius: 50%;
  margin-left: 70vw;
  color: #e6e6e6;
}

.background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
}


@keyframes Rose {
  from {
    transform: translateX(100%);
    /* transform: translateX(-300%); */
  }
  to {
    transform: translateX(-600%);
    /* transform: translateX(100%); */
  }
}

@keyframes Par {
  from {
    transform: translateX(300%);
    /* transform: translateX(-300%); */
  }
  to {
    transform: translateX(-400%);
    /* transform: translateX(100%); */
  }
}

@keyframes Choix {
  from {
    transform: translateX(450%);
    /* transform: translateX(-300%); */
  }
  to {
    transform: translateX(-250%);
    /* transform: translateX(100%); */
  }
}

</style>
