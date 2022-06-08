<template>
  <v-container>
    <v-row no-gutters style="height: 300px;">
      <v-col class="text-center" cols="12">
        <v-avatar size="100px" class="mt-10">
          <v-img src="/profile.jpg" max-height="150" max-width="250" />
        </v-avatar>
        <blockquote class="blockquote">
          &#8220;Once you’ve accepted your flaws, no one can use them against you.&#8221;
          <footer>
            <small>
              <em>Timotius &mdash; Business Analyst</em>
            </small>
          </footer>
        </blockquote>
        <v-spacer></v-spacer>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12">
        <v-card>
          <v-tabs color="white accent-4" class="mt-20">
            <v-tab>My Story</v-tab>
            <v-tab>Personal Information</v-tab>
            <v-tab>Abstract</v-tab>

            <v-tab-item>
              <v-container fluid>
                <v-row>
                  <v-text class="ml-5 mt-3 mb-3">
                    Saya adalah seorang <i>technology enthusiast</i> yang selalu tertarik dengan hal yang baru dan
                    menarik untuk dipelajari. <br />
                    Hal-hal yang saya suka selain teknologi adalah <i>travelling around the world</i> khususnya negeri
                    tercinta kita Indonesia Raya.<br />
                    Google Cloud Platform adalah hal yang baru untuk saya, tetapi saya merasa tertantang untuk
                    mempelajarinya. Terimakasih atas kesempatan ini.
                  </v-text>
                </v-row>
              </v-container>
            </v-tab-item>

            <v-tab-item>
              <v-container fluid>
                <v-row>
                  <v-container>
                    <v-row>
                      <v-col cols="5">
                        <v-text>
                          <strong>Umur</strong>
                        </v-text>
                      </v-col>
                      <v-col cols="2">
                        <v-text>
                          <strong>:</strong>
                        </v-text>
                      </v-col>
                      <v-col cols="5">
                        <v-text>
                          <strong>30 th</strong>
                        </v-text>
                      </v-col>
                    </v-row>
                    <v-divider inset></v-divider>
                  </v-container>
                </v-row>
              </v-container>
            </v-tab-item>
          </v-tabs>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'InspirePage'
}
</script>
<style>
div .v-main__wrap {
  background-color: #0d5149;
}
</style>
