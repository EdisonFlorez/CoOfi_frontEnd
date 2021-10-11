<template>
  <div class="offers">
    <Header />
    <Canvas/>
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
};
</script>
