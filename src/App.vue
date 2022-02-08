<template>
  <div id="app">
    <header-box />
    <jumbo-tron />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboTron
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
</style>
