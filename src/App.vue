<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <v-toolbar-title>Most Used Words</v-toolbar-title>
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
      </v-btn>
    </v-app-bar>

    <v-content>
      <home/>
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home'
export default {
  name: 'App',

  components: {
    Home
  },
  data: () => ({
    //
  }),
};
</script>
