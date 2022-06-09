<template>
  <v-card>
    <v-img src="/bg1.jpg" style="height:200px;padding-top:75px">
      <v-card-title class="text-center justify-center py-6">
        <h1 class="font-weight-bold text-h2 basil--text">
          My Favorite
        </h1>
      </v-card-title>
    </v-img>
    <v-tabs color="white accent-4" right>
      <v-tab>Movie</v-tab>
      <v-tab>TV</v-tab>
      <v-tab>Travelling</v-tab>

      <v-tab-item>
        <v-container fluid>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/mv1.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      Justice League Znyder's Cut
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>Justice League Zack Snyder</i> </strong> dirilis di HBO Max di Amerika Serikat pada 18
              Maret 2021.
              Sebagian besar kritikus menganggapnya lebih unggul dari versi teater 2017.
              Dalam The Hollywood Reporter, konsensus kritis digambarkan sebagai memuji
              <i>"gaya penyutradaraan Snyder dan kemampuan untuk menawarkan lebih banyak kedalaman pada karakter" </i>
              tetapi mengkritik durasi film yang panjang.Film ini didedikasikan untuk mengenang putri Snyder, Autumn.
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/mv2.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      Inception
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>Inception</i> </strong> adalah film fiksi ilmiah tahun 2010 yang disutradarai oleh
              Christopher Nolan dan diproduseri oleh <i>Christopher Nolan</i> dan <i>Emma Thomas.</i>
              Naskah film ini ditulis oleh <i>Christopher Nolan</i>. Film ini dibintangi oleh <i>Leonardo DiCaprio,
                Joseph Gordon-Levitt, Elliot Page, Tom Hardy,
                Ken Watanabe, Cillian Murphy, Marion Cotillard, Tom Berenger dan Michael Caine.</i>
              Film Inception ditayangkan secara perdana di Odeon Leicester Square pada tanggal 8 Juli 2010 dan dirilis
              di Amerika Serikat dan Britania Raya pada tanggal 16 Juli 2010.[3] Film ini mendapatkan review positif
              dari para kritikus.
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/mv3.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      The Dark Knight
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>The Dark Knight</i> </strong> dianggap sebagai salah satu film terbaik dalam dekadenya dan
              salah satu dari terhebat dan paling berpengaruh sepanjang masa,
              film ini menerima pujian kritis untuk skenario, gaya visual, skor musik, aksi, tema dewasa, Akting
              (terutama Ledger), sinematografi,
              urutan aksi dan arahan. Film ini juga mencetak banyak rekor selama pemutaran teaternya.[6] <i>The Dark
                Knight</i> muncul di 287 daftar sepuluh besar kritikus,
              lebih banyak daripada film lain tahun 2008 kecuali WALL-E , dan lebih banyak kritikus (77)
              menobatkan <i>The Dark Knight</i> sebagai film terbaik yang dirilis tahun itu.
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>

      <v-tab-item>
        <v-container fluid>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/tv1.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      Game of Thrones
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>Game of Thrones</i> </strong> adalah serial televisi drama fantasi Amerika Serikat yang
              diciptakan oleh <i>David Benioff</i> <i>dan D. B. Weiss</i>
              untuk saluran HBO. Serial ini merupakan adaptasi dari A Song of Ice and Fire, seri novel fantasi karangan
              <i>George R. R. Martin</i>,
              novel pertama adalah A Game of Thrones. Serial ini diproduksi dan difilmkan di Belfast dan tempat lainnya
              di Britania Raya.
              Lokasi syuting juga meliputi Kanada, Kroasia, Islandia, Malta, Maroko, dan Spanyol.
              Game of Thrones ditayangkan perdana di HBO Amerika Serikat pada tanggal 17 April 2011,
              dan berakhir pada 19 Mei 2019, dengan total 73 episode ditayangkan selama delapan musim.
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/tv2.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      Stranger Things
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>Stranger Things</i> </strong> memang menjadi serial yang memiliki genre fiksi ilmiah
              berbalut thriller dan kerap menampilkan
              sejumlah monster mengerikan setiap musimnya. Namun, musim keempat serial <i>original</i> Netflix ini punya
              suasana yang lebih gelap
              dan mencekam ketimbang beberapa musim sebelumnya. Malahan, genre pada musim keempatnya lebih tepat
              terbilang sebagai horor.
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="6" sm="4">
              <v-hover v-slot="{ hover }">
                <v-img :aspect-ratio="4 / 3" src="/tv3.jpg">
                  <v-expand-transition>
                    <div v-if="hover"
                      class="d-flex transition-fast-in-fast-out black v-card--reveal text-h3 white--text text-center"
                      style="height: 100%;">
                      The Witcher
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-hover>
            </v-col>
            <v-col><strong><i>The Witcher </i> </strong> 
            adalah sebuah seri televisi drama-fantasi yang dibuat oleh Lauren Schmidt Hissrich, 
            berdasarkan seri novel yang sama karangan penulis Polandia Andrzej Sapkowski. 
            Bertempat di daratan fiksi yang terinspirasi abad pertengahan yang dikenal sebagai "Benua", 
            The Witcher mengeksplorasi legenda Geralt of Rivia dan Putri Ciri, yang terhubung satu sama lain oleh takdir.
            Dibintangi Henry Cavill, Freya Allan dan Anya Chalotra.
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container fluid>
          <div class="gallery">
            <h1 class="subtitle-1 grey--text pa-2 d-flex justify-center">Labuan Bajo</h1>
            <v-divider></v-divider>
            <v-container class="my-5">
              <div>
                <v-row>
                  <v-col v-for="item in items" :key="item.id" class="d-flex child-flex" cols="4">
                    <v-img :aspect-ratio="4 / 3" :src="item.src" contain class="black lighten-2"
                      @click="selectedItem = item">
                      <template v-slot:placeholder>
                        <v-row class="fill-height ma-0" align="center" justify="center">
                          <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                        </v-row>
                      </template>
                    </v-img>
                    <v-overlay v-if="selectedItem">
                      <v-img :src="selectedItem? selectedItem.src :''" contain @click="selectedItem = null"></v-img>
                    </v-overlay>
                  </v-col>
                </v-row>
              </div>
            </v-container>

          </div>
        </v-container>
      </v-tab-item>
    </v-tabs>
  </v-card>
</template>
<style>
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .8;
  position: absolute;
  width: 100%;
}

@media only screen and (max-width: 413px) {

  .v-application .text-h3 {
    font-size: 2em !important;
    line-height: 2.125rem !important;
  }

}
</style>
<script>

export default {
  name: 'Gallery',
 
  data(){
    return {
      selectedItem: null,
      items: [
        {id: 1, src: require("../static/bajo1.jpg")},
        {id: 2, src: require("../static/bajo2.jpg")},
        {id: 3, src: require("../static/bajo3.jpg")},
        {id: 4, src: require("../static/bajo4.jpg")},
        {id: 5, src: require("../static/bajo5.jpg")},
        {id: 6, src: require("../static/bajo6.jpg")},
        {id: 7, src: require("../static/bajo7.jpg")},
        {id: 8, src: require("../static/bajo8.jpg")},
        {id: 9, src: require("../static/bajo9.jpg")}
      ]
    }
  }
 
}

</script>