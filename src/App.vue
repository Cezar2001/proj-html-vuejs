<template>
  <div id="app">
    <header-box />
    <jumbo-tron />
    <main-container />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboTron from './components/JumboTron.vue'
import MainContainer from './components/MainContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboTron,
    MainContainer,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
</style>
