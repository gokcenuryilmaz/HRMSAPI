<template>
  <div id="app">
    <headerGny></headerGny>
    <UsersGny></UsersGny>
    <footerGny></footerGny>
  </div>
</template>

<script>
import UsersGny from "./components/UsersGny.vue";
import footerGny from "./components/footerGny.vue";
import headerGny from "./components/headerGny.vue";
export default {
  name: 'App',
  components : {
    UsersGny,
    footerGny,
    headerGny
  }
}
</script>

<style>

</style>
