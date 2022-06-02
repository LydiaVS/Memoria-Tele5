<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Rótulos</h1>
    <p>Para la realización de los rótulos se empleó una retícula con las que poder ir estructurando las diferentes piezas viasuales.
      <br> A partir de aquí decidimos crear pastillas solidas jugando con una jerarquía de color para llamar la atención sobre los diferentes elementos informativos.
    </p>
    <img class="tamaño" src="../assets/img/reticula.jpg" alt="">
    <h2>Pantallas con guías</h2>
    <img class="tamaño" src="../assets/img/pantallasguias.jpg" alt="">
    <img class="tamaño" src="../assets/img/doblespantallas.jpg" alt="">
    <img class="tamaño" src="../assets/img/doblespantallas-guias.jpg" alt="">
    <img class="tamaño" src="../assets/img/rotulo1.jpg" alt="">
    <img class="tamaño" src="../assets/img/rotulo2.jpg" alt="">

  </div>
</div>
  
</template>
<script>
import VideoPlayer from 'nuxt-video-player'

//require('nuxt-video-player/src/assets/css/main.css')

export default{
components: {
    VideoPlayer
}

}
</script>
<style lang="sass">
  .tamaño
    @apply max-w-lg
  p
    @apply mb-10
</style>