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
          <li id="services-text">Servicios</li>
        </router-link>
        <span class="user-avatar" v-if="user_log">muestra</span>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data: () => {
    return {
      user_log: false,
    };
  },
};
</script>
<style scoped>
.user-avatar {
  display: block;
  background: orangered;
}
</style>
