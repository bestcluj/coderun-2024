<template>
  <v-container class="homepage-bg mt-lg-16" style="padding: 0; margin:0;">
    <NavBar />
    <v-row>
      <v-col class="font columns" align-self="center">
        <h1>IT MARATHON</h1>
      </v-col>
    </v-row>
    <v-row>
      <v-col align-self="center" class="columns">
        <v-img src="../assets/coderun.svg" max-height="70%" max-width="70%" style="object-position: center" ></v-img>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="font columns" align-self="center">
        <h1>DATA FRUMOASA</h1>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

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

</style>