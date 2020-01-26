<template>
  <div>
    <v-container fluid>
      <v-img
        class="d-lg-none"
        src="/logoHondaBanzai.png"
        height="51.3px"
        aspect-ratio="1.7"
        contain
      ></v-img>
      <div class="d-lg-none">
        <div class="row justify-center">
          <div class="d-inline-bloc font-italic headline grey--text">Central de Atendimento</div>
        </div>

        <div class="font-italic display-1 text-center red--text">(31) 3123-1234</div>
      </div>

      <v-row justify="space-around">
        <v-col class="d-none d-lg-block" cols="5">
          <v-img src="/logoHondaBanzai.png" height="51.3px" aspect-ratio="1.7" contain></v-img>
        </v-col>

        <v-col class="d-none d-lg-block" cols="5">
          <div>
            <div class="row justify-center">
              <div class="d-inline-bloc font-italic headline grey--text">Central de Atendimento</div>
            </div>

            <div class="font-italic display-1 text-center red--text">(31) 3123-1234</div>
          </div>
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