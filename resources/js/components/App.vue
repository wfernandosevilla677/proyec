<template>
    <main>
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <div class="container-fluid">

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">

                    <li class="nav-item">
                        <router-link exact-active-class="active" to="/Login" class="nav-link">Login</router-link>
                    </li>
                    <li>
                        <router-link exact-active-class="active" to="/Registro" class="nav-link">Registro</router-link>
                    </li>
                        <router-link exact-active-class="active" to="/blogs" class="nav-link">Categoria</router-link>
                    </li>
                     <li class="nav-item">
                        <router-link exact-active-class="active" to="/author" class="nav-link" aria-current="page">Autores</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link exact-active-class="active" to="/areas" class="nav-link">Areas</router-link>
                    </li>

                      <li class="nav-item">
                        <router-link exact-active-class="active" to="/editorial" class="nav-link">Editorial</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link exact-active-class="active" to="/educational_level" class="nav-link">Nivel Educativo</router-link>
                    </li>
                     <li class="nav-item">
                        <router-link exact-active-class="active" to="/typematerial" class="nav-link">Tipo de material</router-link>
                    </li>
                     <li class="nav-item">
                        <router-link exact-active-class="active" to="/contacto" class="nav-link">Perfil</router-link>
                    </li>

                     <li class="nav-item">
                        <router-link exact-active-class="active" to="/descargas" class="nav-link">Descargas</router-link>
                    </li>
                                         <li class="nav-item">

                    <li>
                        <router-link exact-active-class="active" to="/Inicio" class="nav-link">Inicio</router-link>
                    </li>

                </ul>

                </div>
            </div>
        </nav>
        <div class="container mt-5">
            <router-view></router-view>
        </div>
    </main>
</template>

<script>
    export default {}
</script>
