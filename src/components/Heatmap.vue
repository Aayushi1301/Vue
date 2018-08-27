<template>

  <!-- Initializing the props of vue-google-heatmap -->
  <vue-google-heatmap :points="points"
                      :height="600"
                      :width="1275"
                      :initialZoom="2"
                      :lat="48.0196"
                      :lng="66.9237"
                       />
</template>

<script>
  //importing the packages
  import Vue from 'vue';
  import VueGoogleHeatmap from 'vue-google-heatmap';

  Vue.use(VueGoogleHeatmap, {
    apiKey:"AIzaSyCdsCZwgVbKBnvwqtPQ8Mqcv5P0lNzuxs8"
  });

  //declaring the component which can be reused later
  export default{
    props:['points']
  }
</script>
