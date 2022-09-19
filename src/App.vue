<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <h3>AmpathUzima</h3>

      <v-spacer></v-spacer>

      
        <span class="mr-2">@user</span>
        <v-icon></v-icon>
    </v-app-bar>

    <v-main>
      <RegForm/>
    </v-main>
  </v-app>
</template>

<script>
import RegForm from './components/RegForm';

export default {
  name: 'App',

  components: {
    RegForm,
  },

  data: () => ({
    //
  }),
};
</script>
