<template>
  <v-toolbar color="indigo" dark>
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <router-link to="/">
      <v-toolbar-title class="white--text">Title</v-toolbar-title>
    </router-link>
    <v-spacer></v-spacer>
    <div class="hidden-sm-and-down">
      <v-btn flat>Link One</v-btn>
      <v-btn flat>Link Two</v-btn>
      <router-link to="/login"><v-btn flat>Login</v-btn></router-link>
    </div>
  </v-toolbar>
</template>
