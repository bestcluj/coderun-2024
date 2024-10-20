<template>
  <v-app-bar class="navigation" flat color="#1b2653">
    <v-toolbar-title>
      <router-link to="/" class="white--text links">
        code.run
      </v-toolbar-title>
    </router-link>
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
