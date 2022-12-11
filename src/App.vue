<template>
  <v-app>
    <v-main>
      <MainLayout/>
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import MainLayout from './layouts/MainLayout.vue'

export default {
  name: 'App',

  components: {
    MainLayout,
  },

  data: () => ({
    //
  }),
}
</script>
