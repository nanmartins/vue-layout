<template>
  <v-container fluid class="main-container pa-0 ma-0">
    <HeaderComponent />
    <router-view></router-view>
  </v-container>
</template>

<script>

import HeaderComponent from '@/components/HeaderComponent.vue'
export default {
  name: 'App',
  components: {
    HeaderComponent
  }
}
</script>

<style>

* {
  box-sizing: border-box;
}

body, html {
  margin: 0;
  padding: 0;
}

</style>
