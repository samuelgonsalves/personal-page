<template>
  <div id="app">
    <Header />
    <Main />
    <AboutMe />
    <Skills />
    <Experience />
    <PersonalProjects />
    <ContactMe />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import AboutMe from './components/AboutMe.vue'
import Skills from './components/Skills.vue'
import Experience from './components/Experience.vue'
import PersonalProjects from './components/PersonalProjects.vue'
import ContactMe from './components/ContactMe.vue'

export default {
  name: 'app',
  components: {
    Header,
    Main,
    AboutMe,
    Skills,
    Experience,
    PersonalProjects,
    ContactMe
  }
}
</script>

<style>
#app {
  font-family: Helvetica;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}
body, html {
  height: 100%;
}
</style>

