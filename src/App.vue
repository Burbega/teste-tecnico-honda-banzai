<template>
  <v-app>
    <NavbarTopo />
    <NavbarLogo />
    <Banner1Topo />
    <ConteudoCentral />
    <Banner2 />
    <Carrossel />
    <CardsInferior />

    <v-content>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-content>

    <Rodape1 />
  </v-app>
</template>

<script>
import NavbarTopo from "@/components/NavbarTopo";
import NavbarLogo from "@/components/NavbarLogo";
import Banner1Topo from "@/components/Banner1Topo";
import ConteudoCentral from "@/components/ConteudoCentral";
import Banner2 from "@/components/Banner2";
import Carrossel from "@/components/Carrossel";
import CardsInferior from "@/components/CardsInferior";
import Rodape1 from "@/components/Rodape1";

export default {
  name: "App",
  components: {
    NavbarTopo,
    NavbarLogo,
    Banner1Topo,
    ConteudoCentral,
    Banner2,
    Carrossel,
    CardsInferior,
    Rodape1
  },
  data: () => ({
    //
  })
};
</script>
