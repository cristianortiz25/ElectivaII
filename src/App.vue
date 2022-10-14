<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">Registrar Ingreso</router-link>
  </nav>
  <router-view/>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align:center;
  color: #2c3e50;
}

nav {
  padding: 50px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

.container {
text-align: center;
padding: 5px;
color: #2c3e50;
height:fit-content;
display:block;
}

.registros{
  width: 400px;
  padding: 30px;  
  background: #24303c;
  margin: auto;
  margin-top: 100px;
  border-radius: 4px;
  font-family: 'calibri';
  color: white;
  box-shadow: 7px 13px 37px #000;
}

.registros h4 {
  font-size: 22px;
  margin-bottom: 20px;
}

.controls{
  width: 100%;
  background: #f9f9fa;
  padding: 10px;
  border-radius: 4px;
  margin-bottom: 16px;
  border: 1px solid #aaaaf1;
  font-family: 'calibri';
  font-size: 18px;

}

.registros .botons{
  width: 100%;
  background: #aaaaf1;
  border: none;
  padding: 12px;
  border-radius: 40px;
  margin-bottom: 16px;
  font-size: 16px;
}
</style>
