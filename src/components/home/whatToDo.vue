<template>
  <v-container fluid class>
    <v-layout
      wrap
      align-center
      justify-center
      row
      fill-height
      class="hidden-sm-and-down ma-2 what-do-wrapper"
      style
    >
      <v-flex xs12 sm5 md3 lg3 xl3 class="text-center pa-5">
        <v-hover v-slot:default="{ hover }">
          <v-card class="pa-3" :elevation="hover ? 0 : 0">
            <v-icon size="50px">mdi-microphone</v-icon>
            <p class="google-font my-0" style="font-size:150%;color:#424242">Sessions</p>
            <br />
            <p
              class="google-font"
              style="font-size:100%;color:#9e9e9e"
            >A plethora of talks ranging from technologies like ML, Cloud, Android and Web to Design to Entrepreneurship.</p>
          </v-card>
        </v-hover>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="text-center pa-5">
        <v-hover v-slot:default="{ hover }">
          <v-card class="pa-3" :elevation="hover ? 0 : 0">
            <v-icon size="50px">mdi-lightbulb-on</v-icon>
            <p class="google-font my-0" style="font-size:150%;color:#424242">Ice Breakers</p>
            <br />
            <p
              class="google-font"
              style="font-size:100%;color:#9e9e9e"
            >A series of engaging online activities in between the sessions to combine learning and fun.</p>
          </v-card>
        </v-hover>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="text-center pa-5">
        <v-hover v-slot:default="{ hover }">
          <v-card class="pa-3" :elevation="hover ? 0 : 0">
            <v-icon size="50px">mdi-access-point-network</v-icon>
            <p class="google-font my-0" style="font-size:150%;color:#424242">Stories</p>
            <br />
            <p
              class="google-font"
              style="font-size:100%;color:#9e9e9e"
            >Hear from the community champions about their stories, experiences and learnings.</p>
          </v-card>
        </v-hover>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="text-center pa-5">
        <v-hover v-slot:default="{ hover }">
          <v-card class="pa-3" :elevation="hover ? 0 : 0">
            <v-icon size="50px">mdi-nfc-tap</v-icon>
            <p class="google-font my-0" style="font-size:150%;color:#424242">Discussions</p>
            <br />
            <p
              class="google-font"
              style="font-size:100%;color:#9e9e9e"
            >A variety of discussions through a Panel discussions, Fireside chat and many online conversations.</p>
          </v-card>
        </v-hover>
      </v-flex>
    </v-layout>

    <v-layout
      wrap
      align-center
      justify-center
      row
      fill-height
      class="hidden-sm-and-up"
      style="padding-top:5%;padding-bottom:5%;background:#fafafa"
    >
      <v-flex xs12 sm5 md3 lg3 xl3 class="px-5">
        <span
          class="pa-2 google-font"
          style="border-radius: 7px; background-color: rgb(210, 227, 252); color: rgb(23, 78, 166); font-size: 130%;"
        >Sessions</span>
        <p
          class="google-font mt-3"
          style="font-size:100%;color:#9e9e9e"
        >A plethora of talks ranging from technologies like ML, Cloud, Android and Web to Design to Entrepreneurship.</p>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="px-5 mt-2">
        <span
          class="pa-2 google-font"
          style="border-radius: 7px; background-color: rgb(254, 247, 224); color: rgb(176, 96, 0); font-size: 120%;"
        >Ice Breakers</span>
        <p
          class="google-font mt-3"
          style="font-size:100%;color:#9e9e9e"
        >A series of engaging online activities in between the sessions to combine learning and fun.</p>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="px-5 mt-2">
        <span
          class="pa-2 google-font"
          style="border-radius: 7px; background-color: rgb(252, 232, 230); color: rgb(179, 20, 18); font-size: 120%;"
        >Stories</span>
        <p
          class="google-font mt-3"
          style="font-size:100%;color:#9e9e9e"
        >Hear from the community champions about their stories, experiences and learnings.</p>
      </v-flex>
      <v-flex xs12 sm5 md3 lg3 xl3 class="px-5 mt-2">
        <span
          class="pa-2 google-font"
          style="border-radius: 7px; background-color: rgb(206, 234, 214); color: rgb(13, 101, 45); font-size: 120%;"
        >Discussions</span>
        <p
          class="google-font mt-3"
          style="font-size:100%;color:#9e9e9e"
        >A variety of discussions through a Panel discussions, Fireside chat and many online conversations.</p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>
