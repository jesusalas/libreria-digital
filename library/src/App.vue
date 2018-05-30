<template>
  <div id="app">
    <app-toolbar></app-toolbar>
      <router-view></router-view>
    <app-footer></app-footer>
  </div>
</template>

<script>
/*
import Library from '@/components/Library'
import Login from '@/components/Login'
import User from '@/components/User'
import BookList from '@/components/BookList'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
import AppHome from '@/components/AppHome'
*/

import AppToolbar from '@/components/AppToolbar'
import AppFooter from '@/components/AppFooter'

export default {
  name: 'App',
  components: {AppToolbar, AppFooter}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
