<template>
  <v-card>
    <v-tabs color="deep-purple accent-4" right>
      <v-tab>Landscape</v-tab>
      <v-tab>City</v-tab>
      <v-tab>Abstract</v-tab>

      <v-tab-item>
        <v-container fluid>
          <v-row>
            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
                gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"></v-img>
            </v-col>

            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg">
                <div class="fill-height bottom-gradient"></div>
              </v-img>
            </v-col>

            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg">
                <div class="fill-height repeating-gradient"></div>
              </v-img>
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>

      <v-tab-item>
        <v-container fluid>
          <v-row>
            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
                gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"></v-img>
            </v-col>

            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg">
                <div class="fill-height bottom-gradient"></div>
              </v-img>
            </v-col>

            <v-col cols="6" sm="4">
              <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg">
                <div class="fill-height repeating-gradient"></div>
              </v-img>
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
    </v-tabs>
  </v-card>
</template>