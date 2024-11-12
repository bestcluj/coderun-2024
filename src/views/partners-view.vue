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

      <v-row class="partners">
        <v-col sm="12" md="5" lg="3" class="ma-2">
          <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg white--text"
                  style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
            <img style="height:90%; width:90%" src="../assets/cognizant.png" />
            <v-card-text class="font-mic">
              Cognizant Romania is home to 2500+ creative technologists and is one of Eastern Europe's largest Software Product Engineering delivery networks.
              We serve global clients in several industries, including Banking & Financial Services, Insurance, Healthcare & Life Sciences, Communication Media & Technology,
              and Retail & MLEU (manufacturing, logistics, energy & utilities).
            </v-card-text>
            <v-card-text class="font-mic">
              Our product thinking mindset defines, builds, and launches new, experience-centered software products that reinvent business.
            </v-card-text>
            <v-card-text class="font-mic">
              Cognizant Romania (formerly Cognizant Softvision) was founded in the early 1990s to be the engineering partner for thriving Silicon Valley tech startups.
              The organization prides itself on its great culture and reputation for attracting and developing the best technical talent in Romania and providing all of
              Cognizant with end-to-end delivery expertise. To learn more about Cognizant Romania and explore career opportunities visit our
              <a style="color:cyan" href="https://www.cognizant.com/ro/en" target="_blank"> website!</a>
            </v-card-text>
          </v-card>
        </v-col>

        <v-col sm="12" md="5" lg="3" class="ma-2">
          <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg"
                  style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
            <img style="height:90%; width:90%" src="../assets/zenitech.svg" />
            <v-card-text class="font-mic">
            We design, deliver and implement creative technologies that have real impact on businesses – driving growth, transforming customer experience,
            improving efficiency, reducing time to market and innovating for the future. Learn more about us by visiting our
              <a style="color:cyan" href="https://zenitech.co.uk" target="_blank"> website!</a>
            </v-card-text>
            <v-card-text class="font-mic">
            Zenitech delivers transformational technology by analysing what you want to achieve for your business,
            and then creating and delivering the technology to deliver real and measurable business impact.
            </v-card-text>
            <v-card-text class="font-mic">
            Our end-to-end technology solutions are designed and built by brilliant teams who are located in the UK and Eastern Europe.
            </v-card-text>
          </v-card>
        </v-col>

        <v-col sm="12" md="5" lg="3" class="ma-2">
          <v-card outlined dark class="pa-8 elevation-5 font-faq question-glass-bg"
                  style="border-radius:20px; background-color:rgba(255,255,255, 0%);">
            <img style="height:90%; width:90%" src="../assets/uniqa.jpg" />
            <v-card-text class="font-mic">
              We work with UNIQA on a ‘nearshoring’ basis. Established in 2006, we’re a daughter company of UNIQA and fully integrated with them, yet we still operate as a separate entity.
              That allows us to offer the insights of an independent team allied with the trust and responsiveness of a local provider.
            </v-card-text>
            <v-card-text class="font-mic">
              We support UNIQA with a wide range of projects, from internal systems development to customer-facing technologies for loyalty programs and point-of-sale support.
            </v-card-text>
            <v-card-text class="font-mic">
              We work from our modern offices in central Cluj-Napoca, where our team members benefit from a collaborative culture,
              an ‘open door’ management policy and superb employee benefits. Learn more by visiting our
              <a style="color:cyan" href="https://www.uniqasoftware.ro/" target="_blank">website!</a>
            </v-card-text>
          </v-card>
        </v-col>

      </v-row>

    </v-row>
    <footer-comp />
  </v-container>
</template>

<script>
import navBar from "@/components/nav-bar.vue";
import footerComp from "@/components/footer-comp.vue";
export default {
  name: "schedule-view",
  components:{
    navBar,
    footerComp
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

.font-mic{
  font-family: "Josefin Sans";
  font-size: large;
}

.partners {
  align-items: start;
  justify-items: center;
  justify-content: center;
}

.col .v-card {
  margin: auto;
}

</style>