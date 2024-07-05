<template>
    <v-app-bar :elevation="2">
      <template v-slot:prepend>
        <v-btn icon="mdi-heart"></v-btn>
      </template>
        <v-btn variant="plain" to="/vetements">
          VETEMENTS
        </v-btn>
        <v-btn variant="plain" to="/chaussures">
          CHAUSSURES
        </v-btn>
        <v-btn variant="plain" to="/accessoires">
          ACCESSOIRES
        </v-btn>
        <template v-slot:append>
        <v-btn icon="mdi-account-outline"></v-btn>
        <v-btn icon="mdi-cart-outline²"></v-btn>
      </template>
    </v-app-bar>  
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