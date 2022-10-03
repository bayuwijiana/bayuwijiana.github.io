<template>
  <Navbar />
  <Jumbotron />
  <About />
  <Project />
  <Contact />
  <Footer />

</template>

<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue';
import About from './components/About.vue';
import Project from './components/Project.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    Jumbotron,
    About,
    Project,
    Contact,
    Footer
  }
}
</script>