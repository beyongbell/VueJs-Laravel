<template>
  <v-app>
    <header>
      <v-toolbar>
        <v-toolbar-title>Vue Laravel</v-toolbar-title>
        <div class="flex-grow-1"></div>
        <v-toolbar-items>
          <v-btn text to="/"> Home </v-btn>
          <v-btn text to="about"> About </v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </header>
    <v-content>
      <router-view/>
    </v-content>
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