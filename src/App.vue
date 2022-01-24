<template>
 <Navbar/>
 <Intro/>
<About/>
<Experience/>
<Skills/>
<Projects/>
<Testimonials/>
<Contact/>
<Footer/>

</template>

<script>
import Navbar from './components/Navbar.vue';
import Intro from './components/Intro.vue';
import About from './components/About.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import Projects from './components/Projects.vue';
import Skills from './components/Skills.vue';
import Testimonials from './components/Testimonials.vue';
import Experience from './components/Experience.vue';



export default {
  name: 'App',
  components: {
   Navbar,
   Intro,
   About,
   Contact,
   Footer,
   Projects,
   Skills,
   Testimonials,
   Experience
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
