<template>
  <v-app-bar class="navigation" flat color="#1b2653">
    <v-toolbar-title style="align-content: center;display:flex;">
      <router-link to="/" class="white--text links">
        <img style="max-height:2rem;max-width:100%" src="../assets/cR.png">
      </router-link>
    </v-toolbar-title>

<!--    meniu pentru ecranele mici-->

    <v-menu transition="slide-y-transition" style="align-items: end; display: flex; justify-items: end">
      <template v-slot:activator="{ on }">
        <v-btn class="responsive-menu" icon="mdi mdi-dots-vertical" variant="text"  v-on="on" v-bind="props">
<!--          <v-img src="../assets/menu-icon.svg" style="height:1em; width:1em"></v-img>-->
          <v-icon style="color:#ffffff">mdi-menu</v-icon>
        </v-btn>
      </template>
      <v-list class="menu">
        <v-list-item v-for="(item, i) in items"
                     :key="i"
        >
            <v-list-item-title class="item-title"><router-link :to="item.route" style="text-decoration: none; color:white">{{item.title}}</router-link></v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>

<!--    meniu pentru ecranele mari-->

    <v-row style="display:flex; align-content:end; justify-content:end;">
      <v-col cols="12" class="responsive-row">
        <router-link to="/schedule" class="white--text links ma-4">Schedule</router-link>
        <router-link to="/partners" class="white--text links ma-4">Partners</router-link>
        <a href="https://bestcj.ro/3-5-percent-program/" target="_blank" class="white--text links ma-4">3,5%</a>
      </v-col>
    </v-row>


  </v-app-bar>
</template>

<script>
export default {
  name: "nav-bar",
  data: () => ({
    items: [
      {title: 'Schedule', route:'/schedule'},
      {title: 'Partners', route:'/partners'},
      {title: '3,5%', route: 'https://bestcj.ro/3-5-percent-program/'},
      // {title: 'ABOUT US'}
    ]
  })
}
</script>

<style scoped>

.links{
  color: #ffffff;
  font-family: "josefin sans";
  text-decoration: none;
  font-size: large;
}

.navigation {
  position: sticky;
  display: flex; /* position:sticky automatically makes it inline-flex and breaks its size */
}

.menu{
  background:#5b226a;
  font-family:'josefin sans' !important;
}

@media only screen and (min-width:450px){
  .responsive-menu{
      display:none;
  }
}

@media only screen and (max-width: 449px){
  .responsive-row{
    display:none;
  }
}

.item-title{
  color:#ffffff !important;
}

</style>
