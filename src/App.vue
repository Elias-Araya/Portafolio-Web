<template>
  <div>
   <NavBar />
   <Services />
   <Proyectos />
   <About />
   <Contact />
   <Footer />
   </div>
</template>

<script>
import Services from './components/Services'
import NavBar from './components/NavBar'
import Proyectos from './components/Proyectos'
import About from './components/About'
import Contact from './components/Contact'
import Footer from './components/Footer'
export default {
  name: 'App',

  components: {
    NavBar,
    Services,
    Proyectos,
    About,
    Contact,
    Footer
  },

};
</script>


<style>

</style>
