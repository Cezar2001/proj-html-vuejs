<template>
  <div id="app">
    <header-box :nav="nav"/>
    <jumbo-tron />
    <main-container />
    <news-box />
    <testimonials-box />
    <video-container />
    <contact-us />
    <footer-box 
    :about="about"
    :twitter="twitter"
    :links="links"
    :contact="contact" />
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
        },
        {
          id: '2',
          label: 'PAGES',
        },
        {
          id: '3',
          label: 'BLOG',
        },
        {
          id: '4',
          label: 'SHOP',
        },
        {
          id: '5',
          label: 'EVENTS',
        },
        {
          id: '6',
          label: 'ELEEMENTS',
        },
      ],

      about: [
        {
          id: '1',
          title: 'About',
          text: 'We created Everlead to effectively become the stepping stone towards meeting all your goals & achieving business success',
        }
      ],
        
      twitter:[
        {
          id: '2',
          title: 'Twitter',
          text: '@alisadadm Hi @alisadadm, can you please submit a ticket at hhtps://t.co/JLV61aXG7d and one of our support agent... https://t.co/yk57k1S9bS',
          secondaryText: '@HenrySefaBoakyl Check out our theme Giola which has all necessary elements to build a multi vendor marketplace. https://t.co/c9BIYxZBIL'
        }
      ],

      links: [
        {
          id: '3',
          title: 'Important links',
          me: 'About me',
          us: 'About us',
          language: 'Language packs',
          coach: 'Become a coach',
          events: 'Monthly events',
        }
      ], 

      contact: [
        {
          id: '4',
          title: 'Contact me',
          position: '457 BigBlue Street, NY 10013',
          phone: '(315) 5512-2579',
          mail: 'everlead@mikado.com',
        }
      ], 
    }
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
</style>
