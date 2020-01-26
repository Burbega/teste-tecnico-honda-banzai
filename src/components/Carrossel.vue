<template>
  <v-carousel cycle height="460" show-arrows-on-hover>
    <v-carousel-item v-for="(slide, i) in slides" :key="i">
      <v-sheet class="white" height="100%">
        <v-container fluid>
          <v-row class="fill-height" align="center" justify="center">
            <v-col cols="1"></v-col>

            <v-col class="d-lg-none">
              <v-card class="white" height="370px" max-width="280px">
                <v-img
                  src="/imgVolante.png"
                  class="ml-2"
                  height="180px"
                  width="260px"
                  aspect-ratio="1.7"
                ></v-img>
                <v-card-title
                  class="black--text font-italic subtitle-1 font-weight-bold"
                >Direção com Assistência</v-card-title>
                <v-card-text class="text--primary">
                  <div>Sistema de estabilidade que reforça automaticamente o retorno da direção, auxiliando o motorista em situações onde o carro está ameaçado de instabilidade.</div>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col class="d-none d-lg-block" cols="2">
              <v-card class="white" height="370px" max-width="280px">
                <v-img
                  src="/imgVolante.png"
                  class="ml-2"
                  height="180px"
                  width="260px"
                  aspect-ratio="1.7"
                ></v-img>
                <v-card-title
                  class="black--text font-italic subtitle-1 font-weight-bold"
                >Direção com Assistência</v-card-title>
                <v-card-text class="text--primary">
                  <div>Sistema de estabilidade que reforça automaticamente o retorno da direção, auxiliando o motorista em situações onde o carro está ameaçado de instabilidade.</div>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col class="d-none d-lg-block" cols="2">
              <v-card class="white" height="370px" max-width="280px">
                <v-img
                  src="/vidrosEletricos.png"
                  class="ml-2"
                  height="180px"
                  width="260px"
                  aspect-ratio="1.7"
                ></v-img>
                <v-card-title
                  class="black--text font-italic subtitle-1 font-weight-bold text-break"
                >Vidros elétricos com subida automática</v-card-title>
                <v-card-text class="text--primary">
                  <div>Todas as portas possuem vidros elétricos com a função “um toque” e sistema de segurança antiesmagamento.</div>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col class="d-none d-lg-block" cols="2">
              <v-card class="white" height="370px" max-width="280px">
                <v-img
                  src="/cambioAutomatico.png"
                  class="ml-2"
                  height="180px"
                  width="260px"
                  aspect-ratio="1.7"
                ></v-img>
                <v-card-title
                  class="black--text font-italic subtitle-1 font-weight-bold"
                >Câmbio CVT com Paddle Shift</v-card-title>
                <v-card-text class="text--primary">
                  <div>O câmbio com transmissão CVT de 7 velocidade com Paddle Shift (aletas) proporciona conforto ao trocar de marchas.</div>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col cols="1"></v-col>
          </v-row>
        </v-container>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data() {
    return {
      colors: [
        "indigo",
        "warning",
        "pink darken-2",
        "red lighten-1",
        "deep-purple accent-4"
      ],
      slides: ["First", "Second", "Third", "Fourth", "Fifth"]
    };
  }
};
</script>