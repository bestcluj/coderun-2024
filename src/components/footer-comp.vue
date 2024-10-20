<template>
  <v-footer light class="footer">
    <v-row justify="center" no-gutters>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.instagram.com/best_clujnapoca/" target="_blank"><v-img src="../assets/icons8-instagram.svg"></v-img></a>
      </v-btn>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.linkedin.com/company/best-cluj-napoca" target="_blank"><v-img src="../assets/icons8-linkedin.svg"></v-img></a>
      </v-btn>

      <v-btn
          text
          x-large
          rounded
          class="ma-2"
      ><a href="https://www.facebook.com/BESTcluj" target="_blank"><v-img src="../assets/icons8-facebook.svg"></v-img></a>
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