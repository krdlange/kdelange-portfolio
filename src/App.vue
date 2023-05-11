<template>
  <div>
    <Navigation></Navigation>
    <About></About>
    <Projects></Projects>
    <Contact></Contact>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'MyComponent',
  components: {
    'Navigation': Navigation,
    'About': About,
    'Projects': Projects,
    'Contact': Contact
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&family=Plus+Jakarta+Sans:wght@500;700&display=swap');

</style>