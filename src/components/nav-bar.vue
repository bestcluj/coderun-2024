<template>
  <v-app-bar class="navigation" flat color="#1b2653">
    <v-toolbar-title style="align-content: center;display:flex;">
      <router-link to="/" class="white--text links">
        <img style="max-height:2rem;max-width:100%" src="../assets/cR.png">
      </router-link>
    </v-toolbar-title>
    <v-menu transition="slide-y-transition">
      <template v-slot:activator="{ on }">
        <v-btn icon="mdi mdi-dots-vertical" variant="text"  v-on="on" v-bind="props">
<!--          <v-img src="../assets/menu-icon.svg" style="height:1em; width:1em"></v-img>-->
          <v-icon style="color:#ffffff">mdi-menu</v-icon>
        </v-btn>
      </template>
      <v-list>
        <v-list-item v-for="(item, i) in items"
                     :key="i"
        >
            <v-list-item-title>{{item.title}}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>
  </v-app-bar>
</template>

<script>

// const items = [
//   {title: 'SCHEDULE'},
//   {title: 'PARTNERS'},
//   {title: '3,5%'},
//   {title: 'ABOUT US'}
//
// ]
export default {
  name: "nav-bar",
  data: () => ({
    items: [
      {title: 'SCHEDULE'},
      {title: 'PARTNERS'},
      {title: '3,5%'},
      {title: 'ABOUT US'}
    ]
  })
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
