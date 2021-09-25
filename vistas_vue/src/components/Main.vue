<template>
    <main>
      <h1>CojaOficio</h1>
      <p>
        Todos tenemos un talento, un oficio, unas capacidades; a su vez, también
        tenemos necesidades. CojaOficio es el espacio pensado para conectar esas
        capacidades personales, con las necesidades de otro sector. Es el
        espacio propicio para que puedas aplicar tus habilidades y ganar algo de
        dinero con ello, pero también puedes ser tú quien esté necesitando del
        talento y habilidades de alguien más.
      </p>
      <dialog id="dialog-login">
        <main>
          <h1>CoOfi</h1>
              <form action="">
                  <input type="text" placeholder="Correo electrónico/Usuario:" name="user">
                  
                  <input type="password" placeholder="Contraseña:" name="password">
              </form>
      
              <div class="button-box">
                  <a href="">Olvidé mi contraseña</a>
                  <button id="iniciar" type="submit">Inicia sesión</button>
                  <a href="register.html">Crea tu cuenta</a>
              </div>
          </main>
      </dialog>
      <div class="button-box">
        <button class="crear-cuenta" onclick="window.location.href='register.html'">Crea tu cuenta</button>
        <button class="iniciar-sesion" onclick="mostrarLogin()">Inicia sesión</button>
      </div>
    </main>
</template>

<script>
export default {
    name: 'Main'
}
</script>