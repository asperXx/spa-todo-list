<template>
  <v-app>
    <Navbar />
    <div class="container">

      <router-view />
    </div>
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'App',

  components: {
    Navbar
  },

  data: () => ({
    //
  }),
};
</script>

<style lang="scss">

</style>