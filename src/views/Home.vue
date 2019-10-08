<template>
  <v-layout wrap>
    <v-flex xs12 sm6 md4 v-for="n of 15" :key="n" class="pt-6" >
      <toukou />
    </v-flex>
  </v-layout>
</template>

<script>
import toukou from '../components/heya/toukou.vue'

export default {
  components: {
  toukou,
  },
};
</script>

<style>

</style>
