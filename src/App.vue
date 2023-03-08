<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
  import NavBar from './components/templates/NavBar.vue'
  import Header from './components/templates/Header.vue'
  import Skills from './components/templates/Skills.vue'
  import Projects from './components/templates/Projects.vue'
  import About from './components/templates/About.vue'
  import Contact from './components/templates/Contact.vue'
  import Footer from './components/templates/Footer.vue'
</script>

<template>
  <body id="page-top">
    <div>
      <NavBar/>
    </div>   
      
    <header>
      <Header/>
    </header>

    <div>
      <About/>
    </div>
    <div>
      <Skills/>
    </div>
    <div>
      <Projects/>
    </div>
    <div>
      <Contact/>
    </div>

    <footer>
      <Footer/>
    </footer>
  </body>


</template>

