<template>
  <header>
      <!-- aquí va el logo -->
      
      <a class="logo" href="index.html">CoOfi</a>
    
      <input
        type="text"
        name="search-bar"
        class="search-bar"
        placeholder="Buscar"
      />
      <nav>
        <ul>
          <a href="index.html">
            <li id="start-text">Inicio</li>
          </a>
          <a href="offers.html">
            <li id="offers-text">Ofertas</li>
          </a>
          <a href="services.html">
            <li id="services-text">Servicios</li>
          </a>
        </ul>
      </nav>
    </header>
</template>

<script>

export default {
    name:'Header'    
}
</script>

<style>

</style>