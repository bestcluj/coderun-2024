<template>
  <v-footer light class="footer">
    <v-row justify="center" no-gutters>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.instagram.com/best_clujnapoca/" target="_blank"><v-img src="../assets/igicon.png"></v-img></a>
      </v-btn>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.linkedin.com/company/best-cluj-napoca" target="_blank"><v-img src="../assets/linkedinicon.png"></v-img></a>
      </v-btn>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.facebook.com/BESTcluj" target="_blank"><v-img src="../assets/fbicon.png"></v-img></a>
      </v-btn>

      <v-col class="text-center mt-4" cols="12">
        {{ new Date().getFullYear() }} — <strong>CodeRun</strong>
      </v-col>
    </v-row>

  </v-footer>
</template>

<script>
export default {
name: "footer-comp"
}
</script>

<style scoped>
.footer{
  background-color: #e6acce;
  /*margin-bottom:0 !important;*/
}
</style>