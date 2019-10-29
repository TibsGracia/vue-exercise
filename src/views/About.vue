

<template>
  <v-card class="mx-auto" max-width="344">
    <v-img src="@/assets/image5.png" height="200px"></v-img>

    <v-card-title>
      Mary Grace Tiburillo
    </v-card-title>
    <v-card-actions>
      <v-btn icon @click="show = !show">
        <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>
        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than hecould deliver. You won't have time for sleeping, soldier, not with allthe bed making you'll be doing. Then we'll go with that data file!Hey, you add a one and two zeros to that or we walk! You're going todo his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>

<script>
export default {
  name: "about",
  props:[{name:"Mary Grace",
        about: "I'm a thing. But, like most politicians, he promised more than hecould deliver. You won't have time for sleeping, soldier, not with allthe bed making you'll be doing. Then we'll go with that data file!Hey, you add a one and two zeros to that or we walk! You're going todo his laundry? I've got to find a way to escape."

  }],
  data: () => ({
    show: false,
    info:[{
        
    }]
  })
};
</script>
