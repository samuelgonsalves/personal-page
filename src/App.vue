<template>
  <div id="app">
    <Header />
    <About />
    <PersonalProjects />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import PersonalProjects from './components/PersonalProjects.vue'

export default {
  name: 'app',
  components: {
    Header,
    About,
    PersonalProjects
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
  margin-top: 60px;
}
</style>
