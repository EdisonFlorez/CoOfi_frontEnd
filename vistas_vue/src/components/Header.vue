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
          
            <button v-on:click="irOfertas" id="offers-text">Ofertas</button>
          
          <a href="services.html">
            <li id="services-text">Servicios</li>
          </a>
        </ul>
      </nav>
  </header>
</template>

<script>

export default {
    name:'Header',
    methods:{
      irOfertas: function (){
        var main = document.getElementById("main");
        return main.style.backgroundColor = "black";
      }
    } 
}
</script>

<style scoped>
a{
  text-decoration: none;
}
</style>