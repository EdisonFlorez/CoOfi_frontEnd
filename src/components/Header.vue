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
          <li v-if="active" id="offers-text">Ofertas</li>
          <li v-if="!active" class="active" id="offers-text">Ofertas</li>
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
  },
  data: () => {
    return {
      user_log: false,
    };
  },
};
</script>
<style scoped>
.active {
  color: #91e5f6;
}
.user-avatar {
  display: block;
  background: orangered;
}
</style>
