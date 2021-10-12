<template>
  <div id="app">
    <Header/>
    <main>
      <Hero/>
      <Squares/>
      <Working/>
    </main>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Squares from './components/Squares.vue'
import Working from './components/Working.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Header,
    Squares,
    Working,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/style/common";
@import '~@fortawesome/fontawesome-free/css/all.css';


</style>
