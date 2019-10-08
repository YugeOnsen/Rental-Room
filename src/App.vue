<template>
  <v-app>
    <TheHeader />
    <p class=space_for_header> </p>
    <v-content>
      <router-view />
    </v-content>
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
  padding-top:80px;
  margin-bottom: 0px;
}
</style>
