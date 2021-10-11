<template>
  <div>
    <div class="row">
      <div class="col-3">
        <h2>Usuario</h2>
        <br />
        <button class="btn btn-success">Adjuntar Foto</button>
        <h2>-------------------------</h2>
        <hr />
        <hr />
      </div>
      <div id="vacante" class="col-5">
        <div class="postulate">
          <p id="numero">4 Vacantes</p>
          <p id="disponible">Disponibles ¡Postúlate!</p>
        </div>
        <table class="table table-success table-striped">
          <thead>
            <tr>
              <th scope="col">Cargo</th>
              <th scope="col">Experiencia</th>
              <th scope="col">Fecha de Cierre</th>
              <th scope="col">Postúlate</th>
            </tr>
          </thead>

          <tbody>
            <tr>
              <th scope="row">Carpintero</th>
              <td>24 Meses</td>
              <td>28/09/2021</td>
              <td><button>Aplicar</button></td>
            </tr>
            <tr>
              <th scope="row">Internista</th>
              <td>12 Meses</td>
              <td>1/10/2021</td>
              <td><button>Aplicar</button></td>
            </tr>
            <tr>
              <th scope="row">Medico Veterinario</th>
              <td>6 Meses</td>
              <td>14/10/2021</td>
              <td><button>Aplicar</button></td>
            </tr>
            <tr>
              <th scope="row">Ingeniero industrial</th>
              <td>20 Meses</td>
              <td>21/09/2021</td>
              <td><button>Aplicar</button></td>
            </tr>
          </tbody>
        </table>
      </div>
      <div id="vacante" class="col-4">
        <h4>Total Vacantes en todo el País: 6</h4>
        <div id="pais">
          <img src="../assets/img/pais.png" class="img-thumbnail" alt="" />
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-3">
        <div
          class="nav flex-column nav-pills"
          id="v-pills-tab"
          role="tablist"
          aria-orientation="vertical"
        >
          <a
            class="nav-link active"
            id="v-pills-home-tab"
            data-toggle="pill"
            role="tab"
            aria-controls="v-pills-home"
            aria-selected="true"
            ><router-link style="color: white" to="/profile"
              >Mi Perfil</router-link
            ></a
          >
          <a
            class="nav-link"
            id="v-pills-messages-tab"
            data-toggle="pill"
            href="edit.html"
            role="tab"
            aria-controls="v-pills-messages"
            aria-selected="false"
            >Editar Perfil</a
          >
          <a
            style="color: rgb(255, 0, 0)"
            class="nav-link"
            id="v-pills-messages-tab"
            data-toggle="pill"
            role="tab"
            aria-controls="v-pills-settings"
            aria-selected="false"
            ><router-link style="color: white" to="/offers"
              >Ofertas</router-link
            ></a
          >
          <a
            class="nav-link"
            id="v-pills-settings-tab"
            data-toggle="pill"
            href="rate.html"
            role="tab"
            aria-controls="v-pills-settings"
            aria-selected="false"
            >Calificación</a
          >
          <a
            class="nav-link"
            id="v-pills-settings-tab"
            data-toggle="pill"
            href="index.html"
            role="tab"
            aria-controls="v-pills-settings"
            aria-selected="false"
            >Cerrar Sesion</a
          >
          <hr />
          <hr />
        </div>
      </div>
      <div id="vacante" class="col-9">
        <H3>Mis Postulaciones</H3>
        <table class="table table-info table-striped">
          <thead>
            <tr>
              <th scope="col">#</th>
              <th scope="col">Postulaciones Abiertas</th>
              <th scope="col">Postulaciones Cerradas</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <th scope="col">
                No hay postulaciones abiertas para el candidato
              </th>
              <th scope="col"></th>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navprofile",
};
</script>
