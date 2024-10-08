<template>
  <v-app-bar class="navigation" absolute floating flat color="#1b2653">
    <v-app-bar-title>
      <router-link to="/" class="white--text links">
        code.run
      </router-link>
    </v-app-bar-title>
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