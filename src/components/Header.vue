<template>
  <span>
    <v-toolbar app color="blue lighten-1" dark>
      <v-spacer class="hidden-md-and-up"></v-spacer>
      <router-link to="/">
        <v-toolbar-title
          data-cy="titleBtn"
          class="display-2 mt-3 white--text font-weight-bold"
        >
          {{ appTitle }}
        </v-toolbar-title>
      </router-link>
      <v-spacer class="hidden-sm-and-down"></v-spacer>
      <v-btn flat to="/about" data-cy="signinBtn">About</v-btn>
    </v-toolbar>
  </span>
</template>

<script>
export default {
  name: "AppNavigation",
  data() {
    return {
      appTitle: "ToothBook",
      items: [{ title: "Sign In", url: "/about" }]
    };
  }
};
</script>

<style scoped>
a {
  color: white;
  text-decoration: none;
}
</style>
