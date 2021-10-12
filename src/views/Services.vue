<template>
  <div class="services">
    <Header :active="true" />
    <Offertemplate />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Offertemplate from "../components/Offertemplate.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Services",
  components: {
    Header,
    Offertemplate,
    Footer,
  },
  data: () => {
    return {
      home_page: false,
    };
  },
};
</script>
