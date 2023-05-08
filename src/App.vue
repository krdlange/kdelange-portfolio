<template>
  <div>
    <nav-bar></nav-bar>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'MyComponent',
  components: {
    'nav-bar': NavBar
  }
}
</script>
