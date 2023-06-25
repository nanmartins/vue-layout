<template>
  <v-app>
    <HeaderBody />
    <router-view></router-view>
    <FooterBody />
  </v-app>
</template>

<script>
import HeaderBody from "@/components/HeaderBody.vue";
import FooterBody from "@/components/FooterBody.vue";

export default {
  name: "App",
  components: {
    HeaderBody,
    FooterBody,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

/* body,
html {
  margin: 0;
  padding: 0;
} */
</style>
