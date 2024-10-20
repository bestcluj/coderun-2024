<template>
  <v-container class="ma-0 pa-0 main-cnt" fluid>
    <NavBar />
    <v-row class="homepage-bg">
      <!--    navigation bar-->
<!--      <NavBar />-->
      <!--    first block of content-->
      <v-row class='top-logos'>
        <v-col cols="6">
          <img src="../assets/BESTCJ_signature_white.png" />
        </v-col>
        <v-col cols="6">
          <img src="../assets/UT_Logo_Alb.png" />
        </v-col>
      </v-row>
      <v-row class="ma-0">
        <v-col class="font columns" align-self="center" style="margin-top: 2rem;">
          <h1>Ready to code your way through the urban jungle?</h1>
        </v-col>
      </v-row>
      <v-row>
        <v-col align-self="center" class="columns ma-lg-8 ma-sm-0 pa-0">
          <v-img class="img-responsive" src="../assets/crstrokemic.png" aspect-ratio="8.136" max-height="70%" max-width="70%" style="object-position: center" ></v-img>
          <!-- Aspect ratio computed manally from SVG viewBox dimensions so it renders properly on all browsers -->
        </v-col>
      </v-row>
      <v-row>
        <v-col class="font columns ma-3" align-self="center">
          <h4>November 4-17, 2024</h4>
        </v-col>
      </v-row>
      <v-row>

        <v-col class="font columns ma-3" align-self="center">
          <h4>Pre-register now.</h4>
        </v-col>
      </v-row>

      <!--    register button-->
      <v-row justify="center">
        <v-col class="font columns ma-3">
          <a href="https://forms.gle/6AAK24Tbv6FsPzTR8" style="text-decoration: none" target="_none"><v-card outlined link dark class="pa-6 elevation-5" color="#5d3d94"
                  style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
            REGISTER HERE</v-card></a>
        </v-col>
      </v-row>

<!--      <v-row>-->
<!--        <v-col class="font-2 columns ma-3" align-self="center">-->
<!--          <h3>12 days of trainings and workshops delivered by the best IT companies in Cluj,-->
<!--            2 competition days filled with fun challenges...<br />-->
<!--            ...and the chance to become a winner!-->
<!--          </h3>-->
<!--        </v-col>-->
<!--      </v-row>-->

      <!--    sectiune video-->


      <v-row justify="center" class="mt-lg-16 pb-12 responsive-video">
        <v-col class="columns-video ma-1 mr-lg-4" lg="5" sm="12">
          <v-card outlined dark class="pa-6 elevation-5 responsive-card" color="#e6acce" height="15em"
                  style="border-color: #ffffff; border-width: 1rem; border-radius:20px; font-family: radio stars;">
            <video loop autoplay muted style="height:100%; width:100%;border-color: #ffffff; border-width: 1rem; border-radius:20px;">
              <source src="../assets/videocr3.mp4" type="video/mp4"></video>
          </v-card>
        </v-col>
        <v-col class="columns-video ma-1 ml-lg-4" lg="3" sm="12">
          <v-card outlined dark class="pa-6 elevation-5 font-2 resp-card-2" color="#5d3d94" height="15em"
                  style="border-color: #ffffff; border-width: 1rem; border-radius:20px; display:flex; align-items: center; justify-items: center">
            <h5>12 days of trainings and workshops delivered by the best IT companies in Cluj,
              2 competition days filled with fun challenges...<br />
              ...and the chance to become a winner!</h5>
          </v-card></v-col>

      </v-row>

    </v-row>

<!--    sectiune FAQ-->

    <v-row class="section-2 ma-0">
      <v-col lg="6" sm="10" class="ma-4" style="font-family: 'Radio Stars';">
        <v-card outlined dark class="pa-4 elevation-5" color="#1b2653"
                style="border-color: #ffffff; border-bottom-width: 1rem; border-top-width: .5rem;border-right-width: .5rem;border-left-width: .5rem; border-radius:20px">
        <h1>FREQUENTLY ASKED QUESTIONS</h1></v-card>
      </v-col>
    </v-row>

<!--    Q1-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #1 WHAT IS CODERUN?
      </v-col>
    </v-row>

<!--    <v-row class="section-2 ma-0">-->
<!--      <v-col class="font-ans ml-lg-4">-->
<!--        </v-col>-->
<!--    </v-row>-->

<!--    A1-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          CodeRun is an IT marathon for students who want to test and develop their programming skills, in which participants progress through
          checkpoints located at our partner companies’ headquarters by using their problem solving skills.</v-card>
      </v-col>
    </v-row>

    <!--    Q2-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #2 WHEN AND WHERE DOES CODERUN TAKE PLACE?
      </v-col>
    </v-row>

    <!--    A2-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          November 4-17, 2024, in Cluj-Napoca.</v-card>
      </v-col>
    </v-row>

    <!--    Q3-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #3 HOW DOES CODERUN WORK?
      </v-col>
    </v-row>

    <!--    A3-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          The event is divided into two parts: from November 4-15, there will be online or hybrid training sessions delivered by representatives from
          partner companies, in order to prepare participants for the upcoming challenges. Then, on November 16-17, the actual competition will take place,
          in which participants will have to reach various checkpoints and solve challenges of two
          levels of difficulty: easy and hard. There will be a maximum of 3 checkpoints each day, and each one will take about 2 hours to conquer.</v-card>
      </v-col>
    </v-row>

    <!--    Q4-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #4 WHAT LEVEL OF PROGRAMMING EXPERIENCE DO I NEED TO PARTICIPATE?
      </v-col>
    </v-row>

    <!--    A4-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          Basic knowledge of any programming language is sufficient, and prior experience is not required!
          You will have the opportunity to deepen your existing knowledge or learn new things during the training sessions.</v-card>
      </v-col>
    </v-row>

    <!--    Q5-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #5 WHO WILL JUDGE THE COMPETITION?
      </v-col>
    </v-row>

    <!--    A5-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          The jury will consist of representatives from partner companies, a professor from the Technical University of Cluj-Napoca
          and a professor from the Babeș-Bolyai University.</v-card>
      </v-col>
    </v-row>

    <!--    Q6-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #6 WHO CAN REGISTER FOR CODERUN?
      </v-col>
    </v-row>

    <!--    A6-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          Any student, regardless of their field of study, can participate. Registration can be done individually or in teams of up to 3 students.</v-card>
      </v-col>
    </v-row>

    <!--    Q7-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #7 IF I'M UNDECIDED ABOUT SIGNING UP BY MYSELF, CAN I FIND A TEAM LATER??
      </v-col>
    </v-row>

    <!--    A7-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          Yes, you can sign up with a team until the last registration day (on November 1st). After the registration period closes, you can only find or
          join a team with other participants of the event, during the training period - it’s actually encouraged!</v-card>
      </v-col>
    </v-row>

    <!--    Q8-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #8 CAN I PARTICIPATE AS A HIGH SCHOOL STUDENT?
      </v-col>
    </v-row>

    <!--    A8-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          No, unfortunately CodeRun is aimed only at university students. However, we can’t wait to meet you during your freshman year!</v-card>
      </v-col>
    </v-row>

    <!--    Q9-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #9 WILL ATTENDING CODERUN HELP MY CAREER?
      </v-col>
    </v-row>

    <!--    A9-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          Yes, you will have the opportunity to discuss and come into contact with IT company representatives in Cluj.</v-card>
      </v-col>
    </v-row>

    <!--    Q10-->

    <v-row class="section-2 ma-0">
      <v-col class="font-faq ma-4">
        #10 HOW CAN I REGISTER?
      </v-col>
    </v-row>

    <!--    A10-->

    <v-row class="section-2 ma-0">
      <v-col class="font-ans ma-4">
        <v-card outlined dark class="pa-6 elevation-5" color="#5d3d94"
                style="border-color: #ffffff; border-bottom-width: 2rem; border-top-width: 1rem;border-right-width: 1rem;border-left-width: 1rem; border-radius:20px">
          Keep an eye on our website or BEST Cluj-Napoca’s Instagram page (@best_clujnapoca). Registrations will open soon!</v-card>
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
    }
  }
</script>

/*eslint-disable */

<style>

@import url('https://fonts.cdnfonts.com/css/radio-stars');
@import url('https://fonts.cdnfonts.com/css/josefin-sans');

.homepage-bg{
  background-image: url("../assets/fundal_2.png");
  background-size: cover;
  background-position: center;
  display:block;
  max-width: 100%;
  max-height: 100%;
}

.main-cnt{
  background-size: cover;
  background-position: center;
  display:block;
}

.section-2{
  background-color: #35447f;
}

.columns{
  margin-right:0 !important;
  margin-bottom: 0;
  text-align: center;
  font-size: xx-large;
  align-content:center;
  justify-content: center;
  align-items:center;
  justify-items: center;
  display:flex;
}

.columns-video{
  margin-top: 0;
  text-align: center;
  font-size: xx-large;
}

@media only screen and (max-width: 431px){
  .columns{
    font-size: large;
  }

  .img-responsive{
    height: 100%;
    width:100%;
  }

  .responsive-video{
    display:block;
  }

  .responsive-card{
    height:8em !important;
    width: 13em !important;
  }

  .resp-card-2{
    width:13em !important;
    height: 13em !important;
  }

}

@media only screen and(min-width: 432px){
  .responsive-video{
    /*display:none*/
  }
}

.font{
  font-family: "radio stars";
  color:#ffffff;
}

.font-faq{
  font-family: "radio stars";
  font-size: xx-large;
  color: #cd55a0;
  color: #ea44c3;
}

.font-2{
  font-family: "josefin sans";
  color: white;
}

.font-ans{
  font-family: "josefin sans";
  /*font-size: xx-large;*/
  color:#ffffff;
}

.top-logos .col {
  text-align: center;
}

.top-logos img {
  max-height: 8rem; /* Both logos are large enough in source form to almost certainly be >8rem, so this will always scale them down. */
  max-width: 100%;  /* Limits logos to .col container. At very small widths, prevents the logos from overlapping. */
}

.row {
  margin: unset; /* no-gutters by default */
}

</style>
