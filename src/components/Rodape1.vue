<template>
  <div>
    <v-footer>
      <v-container class="grey lighten-4">
        <v-row class="mb-6" justify="center">
          <v-col md="auto">
            <v-card width="240" height="80" class="pa-2">
              <v-btn icon>
                <v-icon x-large>mdi-map-marker</v-icon>
              </v-btn>
              <span class="caption">Encontre uma</span>
              <div>
                <span class="red--text ml-9">CONCESSIONÁRIA</span>
              </div>
            </v-card>
          </v-col>
          <v-col md="auto">
            <v-card width="240" height="80" class="pa-2">
              <span class="font-italic ml-2">CENTRAL DE ATENDIMENTO</span>
              <div>
                <span class="red--text font-italic headline ml-2">(31) 3123-1234</span>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
    <div class="text-center grey lighten-4 pb-5">
      <p class="font-italic headline">SIGA A BANZAI NAS REDES SOCIAIS</p>

      <v-btn icon>
        <v-icon x-large>mdi-facebook</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon x-large>mdi-instagram</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon x-large>mdi-twitter-circle</v-icon>
      </v-btn>
    </div>

    <v-footer class="white mt-3 pb-3 d-lg-none">
      <v-row no-gutters>
        <v-col cols="12">
          <v-img src="/logoHondaBanzai.png" height="51.3px" aspect-ratio="1.7" contain></v-img>
        </v-col>
      </v-row>
    </v-footer>
    <v-footer class="white mt-3 pb-3 d-lg-none">
      <v-row no-gutters>
        <v-col cols="8">
          <p class="grey--text mt-4 caption">Todos juntos fazem um trânsito melhor</p>
        </v-col>
        <v-col cols="4">
          <v-img
            src="/logo_ibama.png"
            position="left left"
            height="51.3px"
            aspect-ratio="1.7"
            contain
          ></v-img>
        </v-col>
      </v-row>
    </v-footer>

    <v-footer class="white mt-3 pb-3 d-none d-lg-block">
      <v-row no-gutters>
        <v-col cols="6">
          <v-img src="/logoHondaBanzai.png" height="51.3px" aspect-ratio="1.7" contain></v-img>
        </v-col>
        <v-col cols="2">
          <p class="grey--text mt-4">Todos juntos fazem um trânsito melhor</p>
        </v-col>
        <v-col cols="2">
          <v-img
            src="/logo_ibama.png"
            position="left left"
            height="51.3px"
            aspect-ratio="1.7"
            contain
          ></v-img>
        </v-col>
      </v-row>
    </v-footer>
  </div>
</template>