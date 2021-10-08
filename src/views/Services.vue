<template>
  <div class="services">
    <Header :active="true"/>
    <Canvas valorbtn1="Ofrece tu servicio" valorbtn2="Contratar servicio"/>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Canvas from "../components/Canvas.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Services",
  components: {
    Header,
    Canvas,
    Footer,
  },
  data: () => {
    return {
      home_page: false,
    };
  },
};
</script>


