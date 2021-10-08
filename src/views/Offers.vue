<template>
  <div class="offers">
    <Header />
    <Canvas valorbtn1="Publica una oferta" valorbtn2="Aplicar"/>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Canvas from "../components/Canvas.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Offers",
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

<style scoped>
.offers-text {
  color: orangered;
}
</style>
