<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar/>
  </div>
</template>

<script>
import MainRabBar from 'components/content/MainRabBar.vue';

export default {
  name: 'App',
  components: {
    MainRabBar
  }
}
</script>

<style>
@import "/assets/css/base.css";
</style>
