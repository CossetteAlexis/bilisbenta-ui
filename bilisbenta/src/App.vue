<template>
  <div id="app">
    <Navbar/>
    <Home/>
    <About/>
    <HowItWorks/>
    <Benefits/>
    <Packages/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import HowItWorks from './components/HowItWorks'
import Benefits from './components/Benefits'
import Packages from './components/Packages'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Home,
    About,
    HowItWorks,
    Benefits,
    Packages,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Nunito;
}
</style>
