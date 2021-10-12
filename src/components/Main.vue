<template>
  <main>
    <h1>CojaOficio</h1>
    <p>
      Todos tenemos un talento, un oficio, unas capacidades; a su vez, también
      tenemos necesidades. CojaOficio es el espacio pensado para conectar esas
      capacidades personales, con las necesidades de otro sector. Es el espacio
      propicio para que puedas aplicar tus habilidades y ganar algo de dinero
      con ello, pero también puedes ser tú quien esté necesitando del talento y
      habilidades de alguien más.
    </p>

    <div class="button-box">
      <button
        class="crear-cuenta"
        onclick="window.location.href='register.html'"
      >
        Crea tu cuenta
      </button>
      <button class="iniciar-sesion" onclick="mostrarLogin()">
        Inicia sesión
      </button>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped>
main{
  margin-right: 150vw;
}
button {
  width: 10.5em;
  height: 2em;
  border-radius: 2.4em;
  border: none;
  background: #133c55;
  color: white;
  font-family: "Source Serif Pro", serif;
  font-size: 1.4em;
  margin: 5px;
}

</style>
