<template>
  <v-app>
    <NavBar />
    <Footer />
  </v-app>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',

  data: () => ({
    //
  }),
  components: {
    NavBar,
    Footer
  }
}
</script>
