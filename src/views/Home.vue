<template>
  <v-layout wrap>
    <v-flex xs12 sm6 md4 v-for="n in 15" :key="n" class="pt-6" >
      <toukou></toukou>
    </v-flex>
  </v-layout>
</template>

<script>
import toukou from '../components/heya/toukou.vue'

export default {
  components: {
    "toukou" : toukou,
  },
  data: function() {
    return {
      post_data:[
        {
          "user_name":"lawrence",
          "room_location":"okayama",
          "rental_time":"30m",
          "cost":"600",
          "post_time":"keisikiwasureta",
          "user_icom":"./icon/user_id",
          "bookmark":"0", "comment":"IAchan",
          "img":"/img/home"
        },
        {
          "user_name":"onsen",
          "room_location":"tsuyama",
          "rental_time":"12h",
          "cost":"6000",
          "post_time":"keisikiwasureta",
          "user_icom":"./icon/user_id",
          "bookmark":"1",
          "comment":"神通ちゃん",
          "img":"/img/home",
        }
      ]
    }
  }
};
//<v-flex xs12 sm6 md4 v-for="element in posts" :key="element.user_name" :post="element" class="pt-6" >
</script>

<style>

</style>
