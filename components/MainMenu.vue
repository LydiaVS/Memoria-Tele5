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
            <li class="invisibl"><NuxtLink to="/estilo">Estilo gráfico</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/iconos">Iconos</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/animacion">Animación</NuxtLink></li>
          </ul>
        </li>
        <li class="visible" >User Interface</li>
        <li class="visible">Communication Media</li>
        <li class="visible">Corporate Branding</li>
        <li class="visible">Motion pictures</li>

      </ul>
    </div>


  </div>
</template>
<script>
    export default {
        data(){
            return{
                panelIsOpen: false
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
