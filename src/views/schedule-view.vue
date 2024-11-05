<template>
<v-container class="ma-0 pa-0 main-cnt" fluid>
  <nav-bar />
  <v-row class="homepage-bg">

    <v-row class='top-logos'>
      <v-col cols="6">
        <a href="https://bestcj.ro/" target="_blank">
          <img src="../assets/BESTCJ_signature_white.png"></a>
      </v-col>
      <v-col cols="6">
        <a href="https://www.utcluj.ro/" target="_blank">
          <img src="../assets/UT_Logo_Alb.png" /></a>
      </v-col>
    </v-row>

    <v-row>
      <v-col class="ma-2 align-center">
        <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg white--text"
                style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
          WEEK 1: 4-10 NOV
          <v-card-text class="font-mic">
            Nov 6th | 18:00 - 20:00 | Web Requests and Responses
          </v-card-text>
          <v-card-text class="font-mic">
            Nov 7th | 16:00 - 18:00 | From Code to Game -
            beginning 2D Game Programming with SDL 2
          </v-card-text>
          <v-card-text class="font-mic">
            Nov 8th | 16:00 - 18:00 | Workshop: Intro to Arduino Coding
          </v-card-text>
        </v-card>
      </v-col>

      <v-col class="ma-2 align-center">
        <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg"
                style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
          WEEK 2: 11-15 NOV
          <v-card-text class="font-mic">
            Nov 11th | 16:00 - 18:00 | Django + Python for Web Development
          </v-card-text>
          <v-card-text class="font-mic">
            Nov 12th | 16:00 - 20:00 | Your Very Own React Sound Machine by Zenitech
          </v-card-text>
          <v-card-text class="font-mic">
            Nov 13th | 16:00 - 18:00 | Pythonic Playground by Cognizant hosted in-person
          </v-card-text>
          <v-card-text class="font-mic">
            Nov 14th | 16:00 - 20:00 | Identity and Access Management (IAM) by Uniqa Software Services
          </v-card-text>
          <v-card-text class="font-mic">
            TBA | TBA | Workshop: How to Git
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-row>
      <v-col class="ma-2 align-center">
        <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg"
                style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
          COMPETITION DAY 1:
        </v-card>
      </v-col>

      <v-col class="ma-2 align-center">
        <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg"
                style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
          COMPETITION DAY 2:
        </v-card>
      </v-col>
    </v-row>

  </v-row>
<!--  <footer-comp />-->
</v-container>
</template>

<script>
import navBar from "@/components/nav-bar.vue";
// import footerComp from "@/components/footer-comp.vue";
export default {
  name: "schedule-view",
  components:{
    navBar,
    // footerComp
  }
}
</script>

<style scoped>

.main-cnt{
  background-size: cover;
  background-position: center;
  display:block;
}

.homepage-bg{
  background-image: url("../assets/fundal_2.png");
  background-size: cover;
  background-position: center;
  display:block;
  max-width: 100%;
  max-height: 100%;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

.font-faq{
  font-family: "radio stars";
  font-size: x-large;
  color: #ffffff;
  /*color: #cd55a0;*/
  /*color: #ea44c3;*/
}

.font-mic{
  font-family: "Josefin Sans";
  font-size: large;
}

.question-glass-bg{
  max-width:20em;
  min-height:20em;
}

.align-center{
  display:flex;
  align-items:center;
  justify-items:center;
  justify-content:center;
  align-content:center;
}

.theme--dark.v-card > .v-card__text{
  color: rgba(255,255,255, 1)
}

</style>