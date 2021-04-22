<template>
  <full-page id="fullpage" ref="fullpage" :options="options">
    <div class="section">First section ...</div>
    <div class="section">Second section ...</div>
    <div class="section">Third section ...</div>
    <div class="section">Fourth section ...</div>
  </full-page>
</template>

<script>
import Vue from 'vue'
// import 'fullpage.js/vendors/scrolloverflow' // Optional. When using scrollOverflow:true
// import './fullpage.scrollHorizontally.min' // Optional. When using fullpage extensions
import VueFullPage from 'vue-fullpage.js'
Vue.use(VueFullPage)
export default {
  components: {},
}
// cos I might forget them again
// npm run generate
// firebase deploy --only hosting
</script>
