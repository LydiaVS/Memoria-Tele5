<template>
  <div class="side-bar">
    <div class="logo"><LogoMenu/></div>
    <div class="said-main">
      <ul class="main">
        <li  class="visible" id="cero">
           <NuxtLink to="/apariencia">Apariencia de Marca </NuxtLink>
        </li>
        <li @click="panelIsOpen = !panelIsOpen" class="visible" id="open" >
          Marca
          <ul class="panel" v-show="panelIsOpen">
            <li class="invisibl" > <NuxtLink to="/elementos">Elementos Básicos </NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/circulo">Circulo </NuxtLink></li>
            <li class="invisibl" ><NuxtLink to="/colores">Colores </NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/tipo">Tipografía </NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/animacion">Animación</NuxtLink></li>
          </ul>
        </li>
        <li @click="panelIs2Open = !panelIs2Open" class="visible" >Estilos identidad visual
          <ul class="panel" v-show="panelIs2Open">
            <li class="invisibl" > <NuxtLink to="/tipo2">Tipografía</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/colores2">Paleta Colores</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/estilo">Estilo gráfico</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/iconos">Iconos</NuxtLink></li>

          </ul>
        </li>
        <li @click="panelIs3Open = !panelIs3Open" class="visible">Pack Gráfico
          <ul class="panel" v-show="panelIs3Open">
            <li class="invisibl" > <NuxtLink to="/moviles">Elementos móviles</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/cabecera">Cabecera</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/rotulos">Rótulos</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/cortinillas">Cortinillas</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/mosca">Mosca</NuxtLink></li>

          </ul>
        </li>
      </ul>
    </div>


  </div>
</template>
<script>
    export default {
        data(){
            return{
                panelIsOpen: false,
                panelIs2Open: false,
                panelIs3Open: false
            }
        }
    
    }
</script>

<style lang="sass">
  //fuentes
    @import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;500&display=swap');
  .side-bar
    background-color: #135a9a
    width: 40vh
    height: 100vh
    position: fixed
    ul 
      font-family: 'Rubik', sans-serif
      font-size: 12pt
      font-style: 500
      color: white
      li
        font-family: 'Rubik', sans-serif
        font-size: 12pt
        font-style: 500
        color: white
        @apply ml-11 mt-8
        &:hover
          color: #12a4d9
          cursor: pointer
  #cero
    margin-top: 0
  
    
      


</style>
