<template>
  <v-container class="pt-15">
      <v-row style="margin-top:12vh">
          <v-col lg="6">
              <h2 class="intro-text">Welcome to our Vuetify app</h2>
              <p class="description">Lorem ipsum dolor sit amet consectetur,
                   adipisicing elit. Omnis ad eveniet odio
                   Ducimus ratione fuga esse adipisci sint numquam voluptate minus eius.</p>
                   <v-btn color="success" class="white--text mr-10" rounded>Get Started</v-btn>
                   <v-btn color="indigo" class="white--text" rounded>
                       <v-icon>mdi-play-circle</v-icon> Watch Video
                   </v-btn>

          </v-col>
          <v-col lg="6">
              <img width="100%" src="./../assets/hero-img.png" alt="">
          </v-col>
        
      </v-row>
  </v-container>
</template>

<script>
export default {
    name:"Hero-component"
}
</script>

<style scoped>
 h2.intro-text {
     font-size: 60px;
     font-weight: bold;
     font-family: cursive;
     color: #444;
 }
 p.description {
     font-size: 19px;
     font-family: cursive;
     margin: 32px 0px;
     color: #444444ba;
 }
</style>