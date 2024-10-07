<template>
  <v-footer class="footer">
    <v-row justify="center" no-gutters>
      <v-btn
          text
          v-for="link in links"
          :key="link"
          color="white"
          x-large
          outlined
          rounded
          class="ma-2"
      >
        {{ link }}
      </v-btn>
      <v-col class="text-center mt-4" cols="12">
        {{ new Date().getFullYear() }} — <strong>CodeRun</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script setup>
const links = [
  'linkedin',
  'insta',
  'mail',
  'nrtel',
  'utcn',
  'best',
]
</script>

<script>
export default {
  name: "footer-comp",
  data: () => ({
    links: [
      'linkedin',
      'insta',
      'mail',
      'nrtel',
      'utcn',
      'best',
    ],
  }),
}
</script>

<style scoped>
.footer{
  background-color: #e6acce;
}
</style>