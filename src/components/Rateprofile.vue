<template>
    
        <div>

            <div class="row">
                <div class="col-3">
                    

                    <h2>Usuario</h2>
                    <br>
                    <button class="btn btn-success">Adjuntar Foto</button>
                    <h2>-------------------------</h2>
                    <hr>
                    <hr>
        
        
                </div>
                <div id="vacante" class="col-9">
                    <H3>Servicios Contratados</H3>
                        <table class="table table-warning">
                            <thead>
                                <tr>
                                    <th scope="col">#</th>
                                    <th scope="col">Servicio</th>
                                    <th scope="col">Nombre</th>
                                    <th scope="col">Apellido</th>
                                    <th scope="col">@gmail</th>
                                    
                                </tr>
                            </thead>
                                <tbody>
                                    <tr>
                                        <th scope="row">1</th>
                                        <td>Asesoria</td>
                                        <td>Adel</td>
                                        <td>Milan</td>
                                        <td>@yahoo</td>
                                    
                                    </tr>
                                    <tr>
                                        <th scope="row">2</th>
                                        <td>Pintor</td>
                                        <td>Edison</td>
                                        <td>Florez</td>
                                        <td>@hotmail</td>
                                        
                                    </tr>
                                    <tr>
                                        <th scope="row">3</th>

                                        <td>Abogado</td>
                                        <td>Diego</td>
                                        <td>Vargas</td>
                                        <td>@sena</td>
                                    
                                    </tr>
                                    <tr>
                                        <th scope="row">4</th>

                                        <td>Matematico</td>
                                        <td>Carlos</td>
                                        <td>Riascos</td>
                                        <td>@gmail</td>
                                    
                                    </tr>
                                </tbody>
                        </table>
                        
                </div> 
            </div> 
            
            <div class="row">
                <div class="col-3">
        
                    <div class="nav flex-column nav-pills" id="v-pills-tab" role="tablist" aria-orientation="vertical">
                        <a class="nav-link active" id="v-pills-home-tab" data-toggle="pill" role="tab" aria-controls="v-pills-home" aria-selected="true" ><router-link style="color:white;" to="/profile">Mi Perfil</router-link></a>
                        <a class="nav-link" id="v-pills-messages-tab" data-toggle="pill" href="edit.html" role="tab" aria-controls="v-pills-messages" aria-selected="false">Editar Perfil</a>
                        <a style="color:rgb(255,0,0);" class="nav-link"  id="v-pills-messages-tab" data-toggle="pill" role="tab" aria-controls="v-pills-settings" aria-selected="false"><router-link style="color:white;" to="/offers">Ofertas</router-link></a>
                        <a class="nav-link" id="v-pills-settings-tab" data-toggle="pill" href="rate.html" role="tab" aria-controls="v-pills-settings" aria-selected="false">Calificación</a>
                        <a class="nav-link" id="v-pills-settings-tab" data-toggle="pill" href="index.html" role="tab" aria-controls="v-pills-settings" aria-selected="false">Cerrar Sesion</a>
                        <hr>
                        <hr>
                    </div>
                </div>
                <div id="vacante" class="col-9">
                    <H3>Califica tu Servicio....</H3><span class="glyphicon glyphicon-search"></span>
                        <hr>
                        <div id="busqueda">
                            <input
                                type="text"
                                name="search-bar"
                                id="search-bar"
                                placeholder="Seleccionar Item"
                            />
                        </div>
                        <div id="radio">
                            <div class="form-check form-check-inline">
                                <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1">
                                <label class="form-check-label" for="inlineRadio1">1. Muy Insatisfecho</label>
                        </div>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2">
                            <label class="form-check-label" for="inlineRadio2">2. Insatisfecho </label>
                        </div>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
                            <label class="form-check-label" for="inlineRadio3">3. Aceptable </label>
                        </div>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option4">
                            <label class="form-check-label" for="inlineRadio4">4. Satisfecho</label>
                        </div>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option5" >
                            <label class="form-check-label" for="inlineRadio5">5. Muy Satisfecho</label>
                        </div>
                        
                        
                        <button class="btn btn-info">Enviar</button>          
                </div>
            
            </div>
        </div>
    
</template>

<script>
export default {
    name: 'Rate'
    

}

</script>