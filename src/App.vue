<template>
  <v-app>
    <nav-bar></nav-bar>
    <v-main>
      <router-view/>
      
    </v-main>
    <bottam-navbar></bottam-navbar>
  </v-app>
</template>

<script>
import BottamNavbar from './components/BottamNavbar.vue';
import NavBar from './components/NavBar.vue';




export default {
    name: "App",
    data: () => ({
    //
    }),
    components: { BottamNavbar, NavBar }
};



</script>
<style>
@import url('@/assets/styles.css');
</style>