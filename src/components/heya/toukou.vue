<template>
    <v-card
      max-width="344"
      class="mx-auto"
    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">
            {{data.room_location}}
          </v-list-item-title>
          <v-list-item-subtitle>by {{ data.user_name }}</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-img
        src="./IA.jpg"
        height="194"
      ></v-img>

      <v-card-text>
        {{data.comment}}
        <li>
          {{data.rental_time}}
          {{data.cost}}
        </li>
      </v-card-text>

      <v-card-actions>
        <v-btn
          text
          color="deep-purple accent-4"
        >
          Read
        </v-btn>
        <v-btn
          text
          color="deep-purple accent-4"
        >
          Bookmark
        </v-btn>
        <div class="flex-grow-1"></div>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
</template>

<script>
export default {
  components: {
  },
  data: function() {
    return {
      data:{
        "user_name":"lawrence",
        "room_location":"okayama",
        "rental_time":"30m",
        "cost":"600",
        "post_time":"keisikiwasureta",
        "user_icom":"./icon/user_id",
        "bookmark":"0",
        "comment":"IA chanha sekaino shinri nanode minnamo shinkou shiyoune.",
        "img":"/img/home"
      }
    }
  }
}
</script>
