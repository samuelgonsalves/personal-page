<template>
  <div id="app">
    <Header />
    <Main />
    <AboutMe />
    <Skills />
    <Timeline />
    <PersonalProjects />
    <ContactMe />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import AboutMe from './components/AboutMe.vue'
import Skills from './components/Skills.vue'
import Timeline from './components/Timeline.vue'
import PersonalProjects from './components/PersonalProjects.vue'
import ContactMe from './components/ContactMe.vue'

export default {
  name: 'app',
  components: {
    Header,
    Main,
    AboutMe,
    Skills,
    Timeline,
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
.main-header {
    font-size: 3em;
}
</style>

