<template>
  <div >
    <LogIn></LogIn>
  </div>
  <!-- <v-app>
    <v-navigation-drawer v-model="drawer" absolute temporary width="335" class="nav-panel pa-2">
      <v-list-item>
        <v-list-item-avatar>
         some text
        </v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="title">Vuetify</v-list-item-title>
          <v-list-item-subtitle>admin</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

    </v-navigation-drawer>
    <v-app-bar :clipped-left="clipped" fixed app >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
    </v-app-bar>
  </v-app> -->

</template>

<script>
import LogIn from './components/LogIn.vue'

export default {
  name: 'App',
  data() {
    return {
      drawer: false,
      clipped: false,
      items: [
        {
          name: 'Dashboard',
          icon: 'mdi-view-dashboard',
          path: '/dashboard'
        }
      ],
      // token: localStorage.getItem('token')
    }
  },
  components: {
    LogIn
  }
}
</script>

<style>
html {
  font-family: Roboto, sans-serif;
}
</style>
