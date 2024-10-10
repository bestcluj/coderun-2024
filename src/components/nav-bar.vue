<template>
  <v-app-bar class="navigation" absolute floating flat color="#1b2653">
    <router-link to="/" class="white--text links">
      <v-toolbar-title>
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

.navigation{
  position:fixed;
}

</style>
