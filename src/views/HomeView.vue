<template>
  <v-container class="homepage-bg mt-lg-14" style="padding: 0; margin:0;">
<!--    navigation bar-->
    <NavBar />
<!--    first block of content-->
    <v-row>
      <v-col class="font columns" align-self="center">
        <h1>IT MARATHON</h1>
      </v-col>
    </v-row>
    <v-row>
      <v-col align-self="center" class="columns ma-10">
        <v-img src="../assets/coderun.svg" max-height="70%" max-width="70%" style="object-position: center" ></v-img>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="font columns ma-3" align-self="center">
        <h1>DATA FRUMOASA</h1>
      </v-col>
    </v-row>
<!--    register button-->
    <v-row style="display: flex; align-items: center; justify-items: center">
      <v-col class="font columns ma-3" >
<!--        /<v-btn size="x-large" flat color="#5d3d94" class="register-btn">REGISTER HERE</v-btn>-->
        <v-card outlined link dark class="pa-6 register-btn elevation-5" color="#5d3d94" min-width="40rem"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          REGISTER HERE</v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

// width="30rem" height="5rem"

import NavBar from "../components/nav-bar.vue";

  export default {
    name: 'Home-View',

    components: {
      NavBar
    },
  }
</script>
/*eslint-disable */

<style>

.homepage-bg{
  background-image: url("../assets/background.png");
  height:100%;
  width:100%;
  background-size: cover;
  background-position: center;
  display:block;
  max-width: 100%;
  max-height: 100%;
  /*background-repeat: no-repeat;*/
  /*-webkit-background-origin:border;*/
}

/*.register-btn.v-card.v-sheet{*/
/*  outline:30px #ffffff;*/
/*}*/

/*.v-card--link:before{*/
/*  border-radius:20px !important;*/
/*}*/

.columns{
  margin: 5rem;
  margin-bottom: 0;
  text-align: center;
  font-size: xx-large;
  align-content:center;
  justify-content: center;
  align-items:center;
  justify-items: center;
  display:flex;
}

.font{
  font-family: "radio stars";
  color:#ffffff;
}

.theme--dark.v-sheet--outlined {
  /*border: 20px solid #ffffff;*/
}

</style>