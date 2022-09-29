<template>
  <v-app id="inspire">
    <TopMenu />

    <v-main class="grey lighten-3">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import TopMenu from "./components/TopMenu.vue";
export default {
  components: {
    TopMenu,
  },
};
</script>
