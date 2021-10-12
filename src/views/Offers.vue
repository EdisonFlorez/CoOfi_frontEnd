<template>
  <div class="offers">
    <Header />
    <div class="canvas">
      <main>
        <div id="cartelera-servicios" class="cartelera">
          <div
            class="container-entries"
            v-for="(item, index) of offerList"
            :key="index"
          >
            <Offertemplate :offer="item"></Offertemplate>
          </div>

          <div class="button-box">
            <button id="offer-services">Crear una oferta</button>
            <button id="hire-service">Postular a oferta</button>
          </div>
        </div>
      </main>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Offertemplate from "../components/Offertemplate.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Offers",
  components: {
    Header,
    Offertemplate,
    Footer,
  },
  data() {
    return {
      offerList: [],
    };
  },
  created() {
    this.getOffers();
  },
  methods: {
    getOffers() {
      this.axios
        .get("/offer")
        .then((result) => {
          this.offerList = result.data;
          console.log(result.data);
        })
        .catch((err) => {
          console.error(err);
        });
    },
  },
};
</script>
