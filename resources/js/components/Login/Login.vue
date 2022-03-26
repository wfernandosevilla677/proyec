<template>
<form action="">
    <section class="section">
    <section class="formulario">
       <input class="controles" type="email" name="email" id="email" placeholder="Ingrese su nombre de usuario o correo" >
      <input class="controles" type="password" name="password" id="password" placeholder="Ingrese su Contraseña" >
      <input class="buton" type="submit" value="Ingresar">
      <p>¿No tienes cuenta? <router-link to="/Registrarme">Registrarme</router-link></p>
    </section>
    </section>
    </form>
</template>
<style scoped>
*{
    font-family: 'Courier New', Courier, monospace;
    font-size: 1rem;
}

.menu{
  height: 10vh;
}
.section{
  height: 49vh;
}
.footer{
  height: 10vh;
}

*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}

.formulario{
  width: 400px;
  background: #0372f0e8;
  padding: 30px;
  margin: auto;
  margin-top: 5vh;
  margin-right: 200px;
  border-radius: 4px;
  margin-top: 18vh;
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

.formulario .buton{
  width: 100%;
  background: #111010;
  border: none;
  padding: 12px;
  color: white;
  margin: 16px 0;
  font-size: 16px;
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
</style>
