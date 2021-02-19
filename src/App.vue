<template>
  <div id="app">
    <Header></Header>
    <About></About>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Contacts from './components/Contacts.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Contacts,
    Footer,
  },
}
</script>
