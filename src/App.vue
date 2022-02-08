<template>
  <Header />
  <Features/>
  <Organisation/>
  <NewsLetters/>
  <Society/>
  <Testimonials/>
  <Pricing/>
  <Contact/>
  <Footer/>  
</template>

<script>
import Header from './components/Header/main.vue';
import Footer from './components/Footer/main.vue';
import Contact from './components/Contact/main.vue';
import Pricing from './components/Pricing/main.vue';
import Testimonials from './components/Testimonials/main.vue';
import Society from './components/Parteners/main.vue';
import NewsLetters from './components/NewsLetters/main.vue';
import Organisation from './components/Organisation/main.vue';
import Features from './components/Features/main.vue';
import './assets/css/tailwind.css';

export default {
  name: 'App',
  components :{
    Header,
    Contact,
    Pricing,
    Society,
    Testimonials,
    Footer,
    NewsLetters,
    Organisation,
    Features
  }
}
</script>
<style>

</style>
