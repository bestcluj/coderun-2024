<template>
  <v-container class="ma-0 pa-0 main-cnt" fluid style="height:100%; width:100%;">
    <v-row class="homepage-bg mt-lg-14" style="padding: 0; margin:0;">
      <!--    navigation bar-->
      <NavBar />
      <!--    first block of content-->
      <v-row class="ma-0">
        <v-col class="font columns" align-self="center" style="margin-top: 5rem;">
          <h1>IT MARATHON</h1>
        </v-col>
      </v-row>
      <v-row>
        <v-col align-self="center" class="columns ma-lg-8 ma-sm-0 pa-0">
          <v-img src="../assets/coderun.svg" max-height="70%" max-width="70%" style="object-position: center" ></v-img>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="font columns ma-3" align-self="center">
          <h1>DATA FRUMOASA</h1>
        </v-col>
      </v-row>

      <!--    register button-->
      <v-row justify="center">
        <v-col class="font columns ma-3">
          <v-card outlined link dark class="pa-6 elevation-5" color="#5d3d94"
                  style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
            REGISTER HERE</v-card>
        </v-col>
      </v-row>
      <!--    sectiune video-->

      <v-row justify="center" class="mt-lg-16 pb-12">
        <v-col class="columns-video ma-2" cols="7">
          <v-card outlined dark class="pa-6 elevation-5" color="#e6acce"
                  style="border-color: #ffffff; border-width: 1rem; border-radius:20px; font-family: radio stars;">
            video frumos</v-card>
        </v-col>
<!--        <v-col class="columns-video ma-2 ml-10" cols="2">-->
<!--          <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"-->
<!--                  style="border-color: #ffffff; border-width: 1rem; border-radius:20px; font-family: radio stars;">-->
<!--            <v-card-title>-->
<!--              descriere sucara-->
<!--            </v-card-title>-->
<!--            </v-card></v-col>-->

      </v-row>
    </v-row>



<!--    sectiune FAQ-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        FREQUENTLY ASKED QUESTIONS
      </v-col>
    </v-row>

<!--    Q1-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #1 CE ESTE CODERUN?
      </v-col>
    </v-row>

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ml-lg-4">
        descriere mai micuta al carui scop imi este necunoscut momentan
      </v-col>
    </v-row>

<!--    A1-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          oumaigad este un MARATON!!!! de IT</v-card>
      </v-col>
    </v-row>

    <!--    Q2-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #2 CINE E IN CT??????
      </v-col>
    </v-row>

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ml-lg-4">
        descriere mai micuta al carui scop imi este necunoscut momentan
      </v-col>
    </v-row>

    <!--    A2-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          DOAR OAMENI COOL</v-card>
      </v-col>
    </v-row>

    <!--    Q3-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #3 A DOUA INTREBARE
      </v-col>
    </v-row>

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ml-lg-4">
        descriere mai micuta al carui scop imi este necunoscut momentan
      </v-col>
    </v-row>

    <!--    A3-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          OIL UP BBYGIRL</v-card>
      </v-col>
    </v-row>

    <footer-comp />

  </v-container>

</template>

<script>
import NavBar from "../components/nav-bar.vue";
import footerComp from "@/components/footer-comp.vue";

  export default {
    name: 'Home-View',

    components: {
      NavBar,
      footerComp
    },
  }
</script>

/*eslint-disable */

<style>

.homepage-bg{
  /*background-image: url("../assets/background.svg");*/
  background-image: url("../assets/fundal_2.png");
  /*height:100%;*/
  /*width:100%;*/
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



.main-cnt{
  /*height:100%;*/
  /*width:100%;*/
  background-size: cover;
  background-position: center;
  display:block;
  /*max-width: 100%;*/
  /*max-height: 100%;*/
}

.section-2{
  background-color:#5bc5be;
}

.columns{
  /*margin-top: 5rem;*/
  margin-right:0 !important;
  margin-bottom: 0;
  text-align: center;
  font-size: x-large;
  align-content:center;
  justify-content: center;
  align-items:center;
  justify-items: center;
  display:flex;
}

.columns-video{
  /*margin: 5rem;*/
  margin-top: 0;
  text-align: center;
  font-size: xx-large;
  /*align-content:center;*/
  /*justify-content: center;*/
  /*align-items:center;*/
  /*justify-items: center;*/
  /*display:flex;*/
}

.font{
  font-family: "radio stars";
  color:#ffffff;
}

.font-faq{
  font-family: "radio stars";
  font-size: xx-large;
  color: #cd55a0;
}

.font-ans{
  font-family: "josefin sans";
  font-size: xx-large;
  color:#ffffff;
}

.theme--dark.v-sheet--outlined {
  /*border: 20px solid #ffffff;*/
}

</style>