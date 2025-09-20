
<template>
    <v-container grid-list-xs color="red">


  <v-layout style="height: 56px;">
    <Vbar
      v-model="value"
       
      grow
    >
      <v-btn>
        <v-icon>mdi-history</v-icon>

        Recents
      </v-btn>

      <v-btn>
        <v-icon>mdi-heart</v-icon>

        Favorites
      </v-btn>

      <v-btn>
        <v-icon>mdi-map-marker</v-icon>

        Nearby
      </v-btn>
    </Vbar>
  </v-layout>
  </v-container>

</template>
<script setup>
  import { ref } from 'vue'
import 'vuetify/styles'
</script>
<style scoped>

</style>