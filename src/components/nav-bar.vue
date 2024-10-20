<template>
  <v-app-bar class="navigation" flat color="#1b2653">
    <v-toolbar-title style="align-content: center;display:flex;">
      <router-link to="/" class="white--text links">
        <img style="max-height:2rem;max-width:100%" src="../assets/cR.png">
      </router-link>
    </v-toolbar-title>
  </v-app-bar>
</template>

<script>
export default {
  name: "nav-bar"
}
</script>

<style scoped>

.links{
  color: #ffffff;
  font-family: "radio stars";
  text-decoration: none;
}

.navigation {
  position: sticky;
  display: flex; /* position:sticky automatically makes it inline-flex and breaks its size */
}

</style>
