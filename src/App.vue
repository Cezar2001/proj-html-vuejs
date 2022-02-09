<template>
  <div id="app">
    <header-box />
    <jumbo-tron />
    <main-container />
    <news-box />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboTron from './components/JumboTron.vue'
import MainContainer from './components/MainContainer.vue'
import NewsBox from './components/NewsBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboTron,
    MainContainer,
    NewsBox,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
</style>
