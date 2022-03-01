<template>
  <v-app>
    <!-- Header component -->
    <Header/>
    <!-- Hero component -->
    <HeroComponent/>
    <!-- about us component -->
    <Aboutus/>
    <v-main>
      
    </v-main>
  </v-app>
</template>

<script>

import Header from "./components/Header.vue"
import HeroComponent from "./components/HeroComponent.vue"
import Aboutus from "./components/Aboutus.vue"
export default {
  name: 'App',
  components:{Header, HeroComponent,Aboutus}
 

 
};
</script>

