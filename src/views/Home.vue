<template>
  <div class="home">
    <Header/>
    <Main/>
    <div class="about-us"> Un poquito de nosotros
          <p> Somos un equipo de trabajo colombiano, estudiantes con muchas ganas de aprender y progresar en esta bonita tarea que es codificar.
          </p>
      </div>
    <Footer/>    
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>
<style>
@import url('../assets/styles/home-page.css');
a{
  text-decoration: none;
}
</style>