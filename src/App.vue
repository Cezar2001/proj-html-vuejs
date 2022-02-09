<template>
  <div id="app">
    <header-box :nav="nav"/>
    <jumbo-tron />
    <main-container />
    <news-box />
    <testimonials-box />
    <video-container />
    <contact-us />
    <footer-box />
  </div>
</template>

<script>
import ContactUs from './components/ContactUs.vue'
import FooterBox from './components/FooterBox.vue'
import HeaderBox from './components/HeaderBox.vue'
import JumboTron from './components/JumboTron.vue'
import MainContainer from './components/MainContainer.vue'
import NewsBox from './components/NewsBox.vue'
import TestimonialsBox from './components/TestimonialsBox.vue'
import VideoContainer from './components/VideoContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboTron,
    MainContainer,
    NewsBox,
    TestimonialsBox,
    VideoContainer,
    ContactUs,
    FooterBox,
  },
  data() {
    return{

      nav: [
        {
          id: '1',
          label: 'HOMES',
          url: '/HOMES',
        },
        {
          id: '2',
          label: 'PAGES',
          url: '/PAGES',
        },
        {
          id: '3',
          label: 'BLOG',
          url: '/BLOG',
        },
        {
          id: '4',
          label: 'SHOP',
          url: '/SHOP',
        },
        {
          id: '5',
          label: 'EVENTS',
          url: '/EVENTS',
        },
        {
          id: '6',
          label: 'ELEEMENTS',
          url: '/ELEMENTS',
        },
      ],
    }
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
</style>
