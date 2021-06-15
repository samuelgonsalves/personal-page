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
import Vue from 'vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import AboutMe from './components/AboutMe.vue'
import Skills from './components/Skills.vue'
import Timeline from './components/Timeline.vue'
import PersonalProjects from './components/PersonalProjects.vue'
import ContactMe from './components/ContactMe.vue'

import { library } from '@fortawesome/fontawesome-svg-core'
import { faLinkedin } from '@fortawesome/free-brands-svg-icons'
import { faGithub } from '@fortawesome/free-brands-svg-icons'
import { faMedium } from '@fortawesome/free-brands-svg-icons'
import { faEnvelope } from '@fortawesome/free-solid-svg-icons'

import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

library.add(faLinkedin, faGithub, faMedium, faEnvelope)

Vue.component('font-awesome-icon', FontAwesomeIcon)

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
  },
  created () {
    document.title = "Samuel David Gonsalves";
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

