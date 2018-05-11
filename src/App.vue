<template>
  <div id="app">
    <v-header></v-header>
    <div class="tab">tab</div>
    <div class="content">content</div>
    <router-view/>
  </div>
</template>

<script>
import header from './components/header/header.vue'
export default {
  name: 'App',
  components: {
    'v-header': header
  }
}
</script>

<style>
</style>
