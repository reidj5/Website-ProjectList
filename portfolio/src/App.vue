<template>
  <div id="app">
    <Nav/>
    <Projects/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Projects from './components/Projects.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Projects
  }
}
</script>

<style>

</style>
