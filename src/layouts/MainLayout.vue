<template>
  <div class="hello">
    {{msg}}
  </div>
  <v-btn
      depressed
      color="primary"
    >
      Primary
    </v-btn>
</template>

<script>
export default {
  name: 'MainLayout',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
