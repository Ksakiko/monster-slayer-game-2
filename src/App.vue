
<script setup>
import Game from './components/Game.vue'
</script>

<template>
  <header>
    <h1>Monster Slayer</h1>
  </header>
  <main>
    <Game />
  </main>
</template>

<style>

* {
  box-sizing: border-box;
}

html {
  font-family: 'Jost', sans-serif;
}

body {
  margin: 0;
}

header {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  padding: 0.5rem;
  background-color: #880017;
  color: white;
  text-align: center;
  margin-bottom: 2rem;
}
</style>