<template>
  <div class="home">
    <Header />
    <Main />

    <Footer />
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
@import url("../assets/styles/home-page.css");
a {
  text-decoration: none;
}
</style>
