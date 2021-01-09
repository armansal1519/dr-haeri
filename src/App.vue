<template>
  <v-app>
    <v-app-bar app color="#FCF7F7" height="94" dark>
     
    </v-app-bar>

    <v-main>
      <home-page/>
   
    </v-main>
  </v-app>
</template>

<script>
// import HomePage from './components/HomePage'
import HomePage from './components/HomePage.vue';


export default {
  name: "App",

  components: {
    HomePage
  },

  data: () => ({
    //
  })
};
</script>
