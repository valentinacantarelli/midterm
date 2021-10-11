<template>
  <div id="app">
    <Header/>
    <main>
      <Hero/>
    </main>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Header,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/style/common";

</style>
