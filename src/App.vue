<template>
  <div class="page-wrapper"> 
    <Navigation></Navigation>
    <About></About>
    <Projects></Projects>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'MyComponent',
  components: {
    'Navigation': Navigation,
    'About': About,
    'Projects': Projects,
    'Contact': Contact,
    'Footer': Footer
  }
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&family=Plus+Jakarta+Sans:wght@500;700&display=swap');

.page-wrapper {
  margin: 40px 24px;
}

@media only screen and (min-width: 768px) {
    .page-wrapper {
        max-width: 1000px;
        width: 100%;
        margin: 40px auto;
    }
}
</style>