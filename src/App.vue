<template>
  <v-container fluid class="main-container pa-0 ma-0">
    <HeaderBody />
    <router-view></router-view>
  </v-container>
</template>

<script>
import HeaderBody from "@/components/HeaderBody.vue";
export default {
  name: "App",
  components: {
    HeaderBody,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

body,
html {
  margin: 0;
  padding: 0;
}
</style>
