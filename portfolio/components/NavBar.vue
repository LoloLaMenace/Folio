<template>
  <div class="nav">
    <v-app-bar :elevation="2">
      <NuxtLink to="/vetements">
        <v-btn variant="plain">
          VETEMENTS
        </v-btn>
      </NuxtLink>
        
        <v-btn variant="plain">
          CHAUSSURES
        </v-btn>
        <v-btn variant="plain">
          ACCESSOIRES
        </v-btn>
    </v-app-bar>  
  </div>
</template>

<style>
    .nav{
        display: flex;
        justify-content: space-around;
        align-items: center
    }

    .v-toolbar__content, .v-toolbar__extension {
    justify-content: space-around;
}
</style>