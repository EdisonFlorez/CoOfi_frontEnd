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
                <div class="col-9">
                    <H3>Editar Perfil</H3>
                    <H6>Datos Básicos</H6>
                    <input type="text" placeholder="Nombres" class="secc1">
                    <input type="text" placeholder="Apellidos" class="secc1">
                    <input type="text" placeholder="Identificación" class="secc1">
                    
                    
                    <input type="text" placeholder="Correo" class="secc2">
                    <input type="text" placeholder="Dirección" class="secc2">
                    <input type="text" placeholder="Ocupación" class="secc2">
                        <hr>
                            <H6>Formación</H6>    
                            <input type="text" placeholder="Grado de escolaridad" class="secc1">
                            <input type="text" placeholder="Cursos Formales" class="secc1">
                            <input type="text" placeholder="Cursos Informales" class="secc1">
                        <hr>

                            <H6>Experiencia</H6> 
                            <input type="text" placeholder="Ultimo Empleo" class="secc1">
                            <input type="text" placeholder="Años de experiencia" class="secc1">
                            <input type="text" placeholder="Adjuntar Hv" class="secc1">
                        
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
                <div class="col-9">
                    <hr>
                        <div id="grupo">
                            <button class="btn btn-primary">Agregar</button>
                            <button class="btn btn-primary">Actualizar</button>
                            <button class="btn btn-primary">Eliminar</button> 
                        </div>
                        <H6>Iniciar Sesión</H6>  
                            <input type="text" placeholder="USUARIO" class="secc3">
                            <input type="text" placeholder="CONTRASEÑA" class="secc3">
                            <button class="btn btn-danger">Iniciar</button>            
                </div>
            
            </div>
        </div>
    
</template>

<script>
export default {
    name: 'Edit'


}

</script>