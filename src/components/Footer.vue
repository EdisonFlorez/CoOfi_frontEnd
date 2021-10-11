<template>
  <footer>
    <div class="about-us">
      Un poquito de nosotros
      <p>
        Somos un equipo de trabajo colombiano, estudiantes con muchas ganas de
        aprender y progresar en esta bonita tarea que es codificar.
      </p>
    </div>
    <div class="copyright">
      Copyright &copy; 2021 -
      <router-link to="/" class="link">CojaOficio.</router-link>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.link {
  text-decoration: none;
  font-family: "volkhov", serif;
  color: #91e5f6;
}
footer{
  position: absolute;
  bottom: -500px;
}
</style>
