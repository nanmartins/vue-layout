<template>

  <v-app class="header-main-body">
    <v-app-bar app flat :height="56" color="#17130E">

      <v-container fluid class="navbar-body pa-0">

        <router-link to="/" class="logo-link d-flex align-center">
          <v-img
            src="https://res.cloudinary.com/dpskrziq1/image/upload/v1687637046/logo_qo6moj.png"
            :height="40"
            inline>
          </v-img>
        </router-link>

        <!-- <v-btn min-width="0"> -->
          <router-link to="/" class="user-link d-flex align-center">
            <v-img
              src="https://res.cloudinary.com/dpskrziq1/image/upload/v1687642381/user-icon_ozvrft.png"
              :height="26"
              inline>
            </v-img>
          </router-link>
        <!-- </v-btn> -->

      </v-container>

    </v-app-bar>

  </v-app>

</template>

<script>
export default {
  name: "HeaderBody",
};
</script>

<style scoped>

.header-main-body {
  height: 100%;
}

.navbar-body {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 85vw;
}
</style>
