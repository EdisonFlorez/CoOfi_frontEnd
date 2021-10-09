<template>
  <div class="canvas">
    <div class="row">
      <div id="vacante" class="col-1"></div>

      <div id="vacante" class="col-4">
        <div class="postulate">
          <p id="numero"></p>
          <H3>Búsqueda</H3>
          <p id="disponible">Salario en (Millones de Pesos)</p>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="defaultCheck1"
            />
            <label class="form-check-label" for="defaultCheck1">
              Menos de $1
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="defaultCheck2"
            />
            <label class="form-check-label" for="defaultCheck2">
              $1 a $1,5
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="defaultCheck2"
            />
            <label class="form-check-label" for="defaultCheck2">
              $1,5 a $2
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="defaultCheck2"
            />
            <label class="form-check-label" for="defaultCheck2">
              $2 a $2,5
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="defaultCheck2"
            />
            <label class="form-check-label" for="defaultCheck2">
              $A Convenir
            </label>
          </div>
          <br />
          <p id="disponible">Ciudad</p>
          <input type="text" placeholder="Armenia" />
          <br />
          <br />
          <p id="disponible">Fecha de Publicación</p>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios1"
              value="option1"
              checked
            />
            <label class="form-check-label" for="exampleRadios1">
              Hoy y Ayer
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios2"
              value="option2"
            />
            <label class="form-check-label" for="exampleRadios2">
              Hace 1 Semana
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios3"
              value="option3"
            />
            <label class="form-check-label" for="exampleRadios3">
              Hace 2 Semanas
            </label>
          </div>
          <div id="radio" class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios3"
              value="option3"
            />
            <label class="form-check-label" for="exampleRadios3">
              Hace 1 Mes
            </label>
          </div>
          <br />
          <button id="boton4" type="button" class="btn btn-danger">
            FILTRAR
          </button>
          <br />
          <br />
        </div>
      </div>
      <div id="vacante" class="col-1"></div>
      <div id="gestionar" class="col-6">
        <H3>Gestionar Ofertas</H3>
        <H6>Datos Empleo</H6>
        <input type="text" placeholder="Nombre del cargo" class="secc1" />
        <input type="text" placeholder="Empresa" class="secc1" />
        <input type="text" placeholder="Ciudad" class="secc1" />
        <hr />
        <H6>Descripción y Logo</H6>
        <div id="area" class="input-group-prepend">
          <span class="input-group-text">Detalle</span>
        </div>
        <textarea
          id="area"
          class="form-control"
          aria-label="With textarea"
        ></textarea>
        <br />
        <input type="text" placeholder="Adjuntar Logo" class="secc1" />
        <button id="boton3" type="button" class="btn btn-primary">Logo</button>
        <hr />

        <H6>Contrato</H6>
        <input type="text" placeholder="Tipo de Contrato" class="secc1" />
        <input type="text" placeholder="Jornada" class="secc1" />
        <input type="text" placeholder="Salario" class="secc1" />

        <hr />
        <H6>CRUD</H6>
        <div
          id="grupo"
          class="btn-group"
          role="group"
          aria-label="Basic example"
        >
          <button type="button" class="btn btn-secondary">Crear</button>
          <button type="button" class="btn btn-primary">Editar</button>
          <button type="button" class="btn btn-success">Actualizar</button>
          <button type="button" class="btn btn-danger">Eliminar</button>
          <hr />
          <hr />
        </div>
      </div>
    </div>

    <h5>Empleos a Nivel Nacional</h5>
    <br /><br />

    <div id="cartelera-servicios" class="cartelera">
      <div class="container-entries">
        <div class="container-entries2">
          <section>
            <p id="k">Mecanico de Patio</p>

            <p>
              Empresa vinculada al sector transporte requiere técnico o
              tecnólogo automotriz para el cargo de MECÁNICO DE PATIO, con
              experiencia de 3 años en sistema de frenos, líquido y aire,
              embragues, transmisiones y diferenciales, suspensiones rígidas y
              neumáticas
            </p>
            <br />
          </section>
        </div>
        <div id="lista">
          <img src="../assets/img/img1.jpeg" class="img-thumbnail" alt="" />
        </div>
      </div>
      <button id="boton2" type="button" class="btn btn-warning">Aplicar</button>

      <div class="container-entries">
        <div class="container-entries2">
          <section>
            <p id="k">Auxiliar de Bodega</p>

            <p>
              Importante empresa ferretera ubicada en MARINILLA ANTIOQUIA esta
              en búsqueda de BACHILLERES que hayan realizado auxiliares de
              cargue con 1 AÑO DE EXPERIENCIA Responsabilidad de manipular y
              almacenar correctamente.$ 908.526 + prestaciones de ley.
            </p>

            <br />
          </section>
        </div>
        <div id="lista">
          <img src="../assets/img/img2.jpeg" class="img-thumbnail" alt="" />
        </div>
      </div>
      <button id="boton2" type="button" class="btn btn-warning">Aplicar</button>

      <div class="container-entries">
        <div class="container-entries2">
          <section>
            <p id="k">Oficial de Montaje de Redes</p>
            <p>
              Nos encontramos en la búsqueda de técnico en obras de
              telecomunicaciones con experiencia de 1 a 3 años, para desarrollar
              el cargo como OFICIAL DE MONTAJE. Salario básico: $1.113.945 mas
              auxilio de transporte $106.454, horas extras.....
            </p>
          </section>
        </div>
        <div id="lista">
          <img src="../assets/img/img6.png" class="img-thumbnail" alt="" />
        </div>
      </div>
      <button id="boton2" type="button" class="btn btn-warning">Aplicar</button>

      <div class="container-entries">
        <div class="container-entries2">
          <section>
            <p id="k">Psicólogo de Selección</p>

            <p>
              universitario en Psicología, administración de empresas,
              ingeniería industrial o afines con experiencia mínima de 2 años
              manejando procesos de reclutamiento y selección de personal.
              Revisa y hace seguimiento a los procesos de selección e
              indicadores asignados.
            </p>
            <br />
          </section>
        </div>
        <div id="lista">
          <img src="../assets/img/img3.jpg" class="img-thumbnail" alt="" />
        </div>
      </div>
      <button id="boton2" type="button" class="btn btn-warning">Aplicar</button>

      <div class="container-entries">
        <div class="container-entries2">
          <section>
            <p id="k">Ingeniero de Sistemas</p>

            <p>
              Importante Clínica de Tercer Nivel ubicada en la localidad de
              Suba, se encuentra en la búsqueda para su equipo de trabajo de
              Ingeniero de Sistemas con mínimo 3 años de experiencia como
              Administrador de Base de Datos, conocimientos en instalación,
              Salario: 2.700.000
            </p>
            <br />
          </section>
        </div>
        <div id="lista">
          <img src="../assets/img/img5.jpg" class="img-thumbnail" alt="" />
        </div>
      </div>
      <button id="boton2" type="button" class="btn btn-warning">Aplicar</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Canvasofertas",
};
</script>

<style>
.cartelera {
  position: relative;
  width: 80vw;
  height: 85vh;
  margin: 0 10vw;
  background: #91e5f6;
  padding: 0 100px;
  overflow: auto;
}

#lista {
  width: 110px;
  height: 85vh;
  margin-top: -135px;
  margin-left: 20px;
}
#gestionar {
  background: beige;
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
}
.container-entries {
  height: 150px;
  margin: 20px;

  border: 2px solid #133c55;
  border-radius: 9px;
  background: white;
}
.button-box {
  position: sticky;
  bottom: 0;
  padding: 15px;
  background: #91e5f6;
}
#hire-service {
  visibility: visible;
}
.copyright {
  margin-top: 60px;
  padding: 10px;
  background: #133c55;
  text-align: center;
  color: #91e5f6;
}
#k {
  color: red;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 20px;
}

h5 {
  margin-top: 40px;
  color: blue;
  border: black;
  border-block-color: black;
  text-align: center;
  font-size: 35px;
  font-family: fantasy;
  margin-bottom: -50px;
}
.container-entries2 {
  height: 100px;
  margin: 20px;
  margin-left: 160px;
  border: 2px solid #133c55;
  border-radius: 9px;
  background: white;
}
#boton2 {
  width: 150px;
  height: 50px;
  margin-left: 1150px;
}
#boton3 {
  width: 150px;
  margin-left: 30px;
}
#grupo {
  margin-left: 200px;
}
#radio {
  background: white;
}

h6 {
  margin-left: 50px;
  text-align: left;
  color: #d35400;
  font-family: "Gill Sans";
  font-size: 25px;
}

.secc1 {
  margin-left: 30px;
}
</style>
