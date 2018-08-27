<!-- It binds the DOM with the Vue instance data-->

<template>
  <div id="app">
    <google-map></google-map>


  </div>
</template>

<!-- Loading the MyMap component -->
<script>
import Vue from 'vue';
import MyMap from './components/MyMap'
Vue.component('google-map',MyMap)

</script>

