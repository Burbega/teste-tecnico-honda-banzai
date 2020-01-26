<template>
  <div>
    <v-system-bar :height="height" color="grey lighten-3" dense class="grey--text">
      <v-col cols="2"></v-col>
      <v-col class="d-lg-none" cols="2"></v-col>
      <v-btn icon>
        <v-icon color="grey lighten-1">mdi-home</v-icon>
      </v-btn>

      <span class="d-none d-lg-block">Ir para o Portal Banzai</span>

      <v-spacer class="d-none d-lg-block"></v-spacer>
      <v-btn icon>
        <v-icon color="grey lighten-1">mdi-map-marker</v-icon>
      </v-btn>
      <span class="mr-6 d-none d-lg-block">Encontre uma concessionária</span>
      <v-btn icon>
        <v-icon color="grey lighten-1">mdi-email</v-icon>
      </v-btn>
      <span class="d-none d-lg-block">Fale Conosco</span>

      <v-col cols="2"></v-col>
    </v-system-bar>
  </div>
</template>

<script>
export default {
  data: () => ({
    height: 33
  })
};
</script>