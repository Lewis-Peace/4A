<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-btn href="/" text>Home</v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
