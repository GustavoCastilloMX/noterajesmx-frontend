<template>
  <v-row align="center" class="deep-purple lighten-5">
    <v-col cols="12" justify="center" align="center" align-content="center">
      <v-img src="https://firebasestorage.googleapis.com/v0/b/no-te-rajes-mx.appspot.com/o/images%2Ferror_404.svg?alt=media&token=440c392b-0909-43ef-8867-2c6533d2516b" width="60%" />
    </v-col>
    <v-col cols="12" md="12" justify="center" align="center" align-content="center">
      <h1 class="categoria-title">¡UPS!</h1>
      <p class="categoria-title">Lo sentimos, pero esta página no esta disponible.</p>
    </v-col>
  </v-row>
</template>

<script>

export default {
  name: "Error404"
};
</script>

<style lang="css" scoped>
.categoria-title {
  font-family: "Raleway", sans-serif;
  font-weight: 600;
  font-size: 2.5rem;
  color: #24cc89;
}
</style>