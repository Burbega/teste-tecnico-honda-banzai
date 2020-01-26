<template>
  <div>
    <v-container fluid class="d-lg-none text-center">
      <v-row>
        <v-col cols="3"></v-col>

        <p class="font-italic title">A EMOÇÃO DE DIRIGIR LEVA VOCÊ MAIS LONGE</p>
      </v-row>
    </v-container>

    <v-container fluid class="d-none d-lg-block">
      <v-row justify="start">
        <v-col cols="1"></v-col>
        <v-col cols="5">
          <p class="text-left font-italic display-1">A EMOÇÃO DE DIRIGIR LEVA VOCÊ MAIS LONGE</p>
        </v-col>
        <v-col cols="5"></v-col>
      </v-row>
    </v-container>
    <v-container fluid>
      <v-row justify="start">
        <v-col cols="1"></v-col>

        <v-col class="d-none d-lg-block" cols="2">
          <v-card max-width="165px">
            <v-img src="/imgCarroLado.png" height="96px" width="165px" aspect-ratio="1.7"></v-img>
          </v-card>
          <v-card class="mt-2" max-width="165px">
            <v-img src="/imgCarroTraseira.png" height="96px" width="165px" aspect-ratio="1.7"></v-img>
          </v-card>
          <v-card class="mt-2" max-width="165px">
            <v-img src="/imgCarroTeto.png" height="96px" width="165px" aspect-ratio="1.7"></v-img>
          </v-card>
        </v-col>
        <v-img
          class="ml-3 d-lg-none"
          src="/bannerDoisCarros.png"
          width="680px"
          height="212px"
          aspect-ratio="1.7"
          contain
        ></v-img>
        <v-col class="d-none d-lg-block" cols="5">
          <v-img
            class="mt-12"
            src="/bannerDoisCarros.png"
            width="680px"
            height="212px"
            aspect-ratio="1.7"
            contain
          ></v-img>
        </v-col>
      </v-row>
    </v-container>

    <v-container fluid class="d-lg-none text-center">
      <v-row>
        <v-col cols="3"></v-col>

        <p
          class="body-1 font-weight-medium"
        >O novo Civic Geração 10 traz um design único mudando a categoria de sedãs para sempre. Ele garante a melhor dirigibilidade com o máximo em sofisticação e conforto, atribuído por seu design interno e diferenciada ergonomia.</p>
      </v-row>
    </v-container>

    <v-container fluid class="d-none d-lg-block n10">
      <v-row justify="start">
        <v-col cols="1"></v-col>
        <v-col cols="7">
          <p
            class="body-1 text-left font-weight-medium"
          >O novo Civic Geração 10 traz um design único mudando a categoria de sedãs para sempre. Ele garante a melhor dirigibilidade com o máximo em sofisticação e conforto, atribuído por seu design interno e diferenciada ergonomia.</p>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data: () => ({})
};
</script>