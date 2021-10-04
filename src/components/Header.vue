<template>
  <header>
    <!-- aquí va el logo -->

    <router-link to="/" class="logo">CoOfi</router-link>

    <input
      type="text"
      name="search-bar"
      class="search-bar"
      placeholder="Buscar"
    />
    <nav>
      <ul>
        <router-link to="/offers">
          <li id="offers-text">Ofertas</li>
        </router-link>
        <router-link to="/services">
          <li v-if="!active" id="services-text">Servicios</li>
          <li v-if="active" class="active" id="services-text">Servicios</li>
        </router-link>
        <span class="user-avatar" v-if="user_log">muestra</span>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    active: Boolean,
    vista_offer: Boolean,
  },
  data: () => {
    return {
      user_log: false,
    };
  },
};
</script>
<style scoped>
.active{
  background: orange;
}
.user-avatar {
  display: block;
  background: orangered;
}
</style>

