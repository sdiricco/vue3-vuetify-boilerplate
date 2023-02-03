<template>
  <v-app>
    <AppBar />
    <v-main class="bg-grey-lighten-3">
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import AppBar from "./components/AbbBar.vue"
</script>

<style scoped>
</style>
