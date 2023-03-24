<template>
    <div>
      <v-app-bar
        app
        color="orange"
        dark
      >
        <div class="d-flex align-center">
          <v-img
            alt="Vuetify Logo"
            class="shrink mr-2"
            contain
            src="@/assets/logo.png"
            transition="scale-transition"
            width="40"
          />
  
          <p>{{$const.APP_NAME}}</p>
        
        </div>
  
        <v-spacer></v-spacer>
  
        <v-btn text> Login
        </v-btn>
        <v-btn text> <v-icon>mdi-account-circle</v-icon>
        </v-btn>
      </v-app-bar>
  
    </div>
  </template>
  
  <script>
  
  export default {


  }
  
  </script>
  <style lang="scss" scoped>
  
  </style>