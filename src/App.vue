<template>
  <div class="page-wrapper"> 
    <Navigation class="page-element"></Navigation>
    <About class="page-element"></About>
    <Projects class="page-element"></Projects>
    <Contact class="page-element"></Contact>
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

.page-element {
  margin-bottom: 80px;
}
.page-wrapper {
  margin: 40px 16px;
}

@media only screen and (min-width: 768px) {
    .page-wrapper {
        max-width: 1000px;
        width: 100%;
        margin: 0 auto;
        padding: 24px;
    }
}
</style>