<template>
  <div id="app">
    <v-app>
    <NavBar />
    <div class="page">
      <NuxtPage />
    </div>
  </v-app>
  </div>
</template>

<style>
html, body, #app {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
}

.page{
  margin: 10vh;
}
</style>