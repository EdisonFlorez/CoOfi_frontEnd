<template>
  <div class="offers">
    <Header />
    <Canvasofertas />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Canvasofertas from "../components/Canvasofertas.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Offers",
  components: {
    Header,
    Canvasofertas,
    Footer,
  }
};
</script>

<style scoped>
.offers-text {
  color: orangered;
}
</style>
