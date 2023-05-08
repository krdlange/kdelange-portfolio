<template>
  <div>
    <NavBar></NavBar>
    <About></About>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import About from './components/About.vue'

export default {
  name: 'MyComponent',
  components: {
    'NavBar': NavBar,
    'About': About
  }
}
</script>
