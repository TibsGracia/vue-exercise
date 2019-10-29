<template>
  <v-container fluid fill-height class="home-hero" style="max-height: 100vh;">
    <v-layout justify-center align-center column pa-5>
      <div
        class="display-4 font-weight-black white--text text-xs-center"
        style="background: rgba(0,0,0,0.5)"
      >
        We preserve the 
      </div>
      <div
        class="display-4 font-weight-black white--text text-xs-center"
        style="background: rgba(0,0,0,0.5)"
      >
        beautiful smile on you
      </div>
      <div class="display-1 font-weight-bold white--text text-xs-center"></div>
      <div class="text-center">
        <v-btn rounded color="black" dark large>Book Now</v-btn>
      </div>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "HomeHero"
};
</script>

<style scoped>
.home-hero {
  background: url("https://www.pasadenahealthcenter.com/site/wp-content/uploads/2017/02/canstockphoto8509375-1.jpg");
  background-size: cover;
  width: 100%;
  height: 100%;
}
</style>
