<template>
  <v-parallax height="100%" src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" class="pb-20">
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
    <v-row style="margin-bottom:50px;">
      <v-col cols="12">
        <v-card>
          <v-tabs color="white accent-4" class="mt-20">
            <v-tab>My Story</v-tab>
            <v-tab>Personal Information</v-tab>
            <v-tab>Contacts</v-tab>

            <v-tab-item>
              <v-container fluid>
                <v-row>
                  <v-col cols="3">
                    <v-img src="/profile.jpg"></v-img>
                  </v-col>
                  <v-col cols="9">
                    <v-text class="ml-5 mt-3 mb-3">
                      Saya adalah seorang <i>technology enthusiast</i> yang selalu tertarik dengan hal yang baru dan
                      menarik untuk dipelajari. <br />
                      Hal-hal yang saya suka selain teknologi adalah <i>travelling around the world</i> khususnya negeri
                      tercinta kita Indonesia Raya.<br /><br />
                      Selain itu saya juga suka menonton film, <i>tv series</i> yang bertemakan <i>science fiction</i>
                      dan <i>thriller</i>.
                      Film yang paling saya suka adalah Inception, sedangkan untuk <i>tv series</i> adalah
                      <i><strong>Game of Thrones</strong></i>.<br />
                      <v-divider inset></v-divider>
                      Saat ini saya sedang menjalani pekerjaan saya sebagai <i>Business Analyst</i>. Padahal, sebenarnya
                      saya adalah seorang programmer
                      sejak saya lulus kuliah, tetapi saya sangat tertantang di area <i>Solution Analyst</i>
                      ini.<br /><br />
                      Google Cloud Platform adalah salah satu teknologi yang merupakan hal yang baru untuk saya, tetapi
                      saya merasa tertantang untuk
                      mempelajarinya. Terimakasih atas kesempatan ini DICODING.
                    </v-text>
                  </v-col>
                </v-row>
              </v-container>
            </v-tab-item>

            <v-tab-item>
              <v-container fluid>
                <v-row>
                  <v-container>
                    <v-row>
                      <v-col cols="8" style="margin-left:20px">
                        <v-row style="height:30px;padding-top:20px;padding-bottom:20px">
                          <v-text>
                            <strong>Umur</strong>
                          </v-text>
                          <v-text>
                            <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                              : 30 th</strong>
                          </v-text>
                        </v-row>
                        <v-row style="height:30px;padding-top:20px;padding-bottom:20px">
                          <v-text>
                            <strong>No. Handphone</strong>
                          </v-text>
                          <v-text>
                            <strong>&nbsp;&nbsp;&nbsp;&nbsp;: 0811xxxxxx</strong>
                          </v-text>
                        </v-row>
                        <v-row style="height:30px;padding-top:20px;padding-bottom:20px">
                          <v-text>
                            <strong>Email</strong>
                          </v-text>
                          <v-text>
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:
                            <a href="mailto:tiuz.fti@gmail.com"><strong>tiuz.fti@gmail.com</strong></a>
                          </v-text>
                        </v-row>
                      </v-col>
                      <v-col cols="3">
                        <v-img src="/profile1.jpg"></v-img>
                      </v-col>
                    </v-row>
                    <v-divider inset></v-divider>
                  </v-container>
                </v-row>
              </v-container>
            </v-tab-item>
            <v-tab-item>
              <v-container fluid>
                <v-row style="height:100px">
                  <v-col class="text-center"><strong>FIND ME!</strong></v-col>
                </v-row>
                <v-row style="height:200px">
                  <v-col class="text-center">
                    <v-btn href="https://linkedin.com/in/timotius-sianturi-3408a548" target="_blank" color="blue" fab>
                      <v-icon dark>
                        mdi-linkedin
                      </v-icon>
                    </v-btn>
                  </v-col>
                  <v-col class="text-center">
                    <v-btn href="https://www.facebook.com/reyuze.reyuze" target="_blank" color="dark blue" fab>
                      <v-icon dark>
                        mdi-facebook
                      </v-icon>
                    </v-btn>
                  </v-col>
                  <v-col class="text-center">
                    <v-btn href="https://github.com/timotiusre21" target="_blank" color="dark grey" fab>
                      <v-icon dark>
                        mdi-git
                      </v-icon>
                    </v-btn>
                  </v-col>
                </v-row>
              </v-container>
            </v-tab-item>
          </v-tabs>
        </v-card>
      </v-col>
    </v-row>
  </v-parallax>
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
