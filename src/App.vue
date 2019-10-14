<template>
  <div id="app">
    <Header />
    <About />
    <Experience />
    <PersonalProjects />
    <ContactMe />
    <Interests />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Experience from './components/Experience.vue'
import PersonalProjects from './components/PersonalProjects.vue'
import ContactMe from './components/ContactMe.vue'
import Interests from './components/Interests.vue'
export default {
  name: 'app',
  components: {
    Header,
    About,
    Experience,
    PersonalProjects,
    ContactMe,
    Interests
  }
}
</script>

<style>
#app {
  font-family: Helvetica;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
