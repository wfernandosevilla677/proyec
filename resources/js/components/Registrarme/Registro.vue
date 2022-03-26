<template>
<form action="">
<section class="section">
   <!-- <img class="img" src="../assets/niño.jpeg" alt="">-->

    <section class="formulario">
      <h3>FORMULARIO DE REGISTRO</h3>
      <input  class="controles" type="text" name="name" id="name" placeholder="Ingrese su Nombre" >
      <input class="controles" type="email" name="email" id="email" placeholder="Ingrese su Correo" >
      <input class="controles" type="password" name="password" id="password" placeholder="Ingrese su Contraseña" >

    <router-link  to="/Principal">  <input class="buton" type="submit" value="Registrar"></router-link>
      <p><router-link to="/IniciarSesion">Ya tengo cuenta</router-link></p>
    </section>
    </section>
    </form>
</template>

<style scoped>
*{
    font-family: 'Courier New', Courier, monospace;
    font-size: 1rem;
}
.img{
    margin-top: 12vh;
    height:77vh;
    margin-left:9vh;
}
Menu{
 height:10vh;
}
.section{
 display: flex;
}
Footer{
 height:10vh;
}
h3{
  text-align: center;
}
.formulario{
  width: 30%;
  background: #0372f0e8;
  padding: 30px;
  margin: auto;
  margin-top: 12vh;
  margin-right: 8vh;
  border-radius: 4px;
  color: white;

}
.formulario{
  font-size: 22px;
  margin-bottom: 20px;
}
.controles{
  width: 100%;
  background:white;
  padding: 10px;
  border-radius: 4px;
  margin-bottom: 16px;
  border: 1px;
}
.formulario p{
  height: 40px;
  text-align: center;
  font-size: 18px;
}
.formulario a{
  color: white;
  text-decoration: none;
}
.formulario a:hover{
  color: white;
  text-decoration: underline;
}
.formulario .buton{
  width: 100%;
  background: #111010;
  border: none;
  padding: 12px;
  color: white;
  margin: 16px 0;
  font-size: 16px;
}
</style>
