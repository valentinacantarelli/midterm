<template>
  <div id="app">
    <Header/>
    <main>
      <Hero/>
      <Squares/>
      <Working/>
      <Message/>
      <Articles/>
    </main>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Squares from './components/Squares.vue'
import Working from './components/Working.vue'
import Message from './components/Message.vue'
import Articles from './components/Articles.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Header,
    Squares,
    Working,
    Message,
    Articles,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/style/common";
@import '~@fortawesome/fontawesome-free/css/all.css';


</style>
