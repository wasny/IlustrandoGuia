<template>
  <v-container>
    <v-row class="text-center">
      <v-col offset-lg="2" lg="8" md="12">
        <v-main>
          <h1 class="display-3 font-weight-bold mb-3">Projeto de Iniciação Tecnológica</h1>
          <v-img :src="require('../assets/mirian.png')" class="my-3" contain height="500" />
          <v-img :src="require('../assets/ana.png')" class="my-3" contain height="500" />
          <v-img :src="require('../assets/kamila.png')" class="my-3" contain height="500" />
          <v-img :src="require('../assets/wasny.png')" class="my-3" contain height="500" />
        </v-main>
      </v-col>
    </v-row>
  </v-container>
</template>
 
<script>

export default {
  name: "HelloWorld",
  data: () => ({}),
};
</script>

