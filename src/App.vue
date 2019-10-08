<template>
  <v-app>
    <TheHeader />
    <p class="space_for_header"> </p>
    <router-view />
  </v-app>
</template>

<script>
import TheHeader from './components/TheHeader'

export default {
  components: {
    TheHeader
  },
  data: () => ({
  }),
};
</script>

<style>
.space_for_header{
  padding-top:70px;
  margin-bottom:0px;
}
</style>
