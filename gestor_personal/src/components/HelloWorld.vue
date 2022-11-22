<template>
  <v-container class="container">
    <v-card class="my-5" height="100px">
      <v-row>
        <v-col cols="6">
          <v-img src="../assets/Meristation_logo.png" contain> </v-img>
        </v-col>
      </v-row>
      <v-btn
        class="button"
        href="https://as.com/meristation/"
        target="_blanck"
        elevation="5"
        color="orange"
        >Aceptar</v-btn
      >
    </v-card>
    <v-card class="my-5" height="90px">
      <v-row>
        <v-col cols="6">
          <v-img
            src="../assets/logo-hc-new-p.webp"
            contain
            class="my-5"
          ></v-img>
        </v-col>
      </v-row>
      <v-btn
        class="button"
        href="https://www.hobbyconsolas.com/"
        target="_blanck"
        elevation="5"
        color="blue"
        >Aceptar</v-btn
      >
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',

  data: () => ({})
}
</script>

<style scoped>
.button {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.container {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: flex-start;
  /*background-color: black;*/
}
</style>
