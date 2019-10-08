<template>
    <v-card
      max-width="344"
      class="mx-auto"
    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">IAchan KawaIA</v-list-item-title>
          <v-list-item-subtitle>by W_Lawrence</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-img
        src="./IA.jpg"
        height="194"
      ></v-img>

      <v-card-text>
        IA chanha sekaino shinri nanode minnamo shinkou siyoune.
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
