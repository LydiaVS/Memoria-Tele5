<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Rótulos</h1>
    <p>Para la realización de los rótulos se empleó una retícula con las que poder ir estructurando las diferentes piezas viasuales.
      <br> A partir de aquí decidimos crear pastillas solidas jugando con una jerarquía de color para llamar la atención sobre los diferentes elementos informativos.
    </p>
    <img class="tamaño" src="img/reticula.jpg" alt="">
    <h2>Pantallas con guías y espacios</h2>
    <img class="tamaño" src="img/pantallasguias.jpg" alt="">
    <h2>Pantalla con una línea de texto</h2>
    <p>Así es como se generaría cuando al inicio de la noticia solo se presenta un rótulo con una línea de texto y un pequeo resumen de lo que sería la noticia, junto con un video de la animación.</p>
    <img class="tamaño" src="img/rotulo1.jpg" alt="">
    <video-player class="espacio" src="video/pantalla vid 1.mp4"/>
    <h2>Doble línea de texto</h2>
    <p></p>
    <img class="tamaño" src="img/rotulo2.jpg" alt="">
    <h2>Pantallas Dobles</h2>
    <p></p>
    <img class="tamaño" src="img/doblespantallas.jpg" alt="">
    <img class="tamaño espacio"  src="img/doblespantallas-guias.jpg" alt="">
    <h2>Pantalla triplex</h2>
    <p>Este es un uno de los casos donde se necesitaría generar tres tipos de pantallas con sus diferentes rótulos, aquí un ejemplo de como se montaría con imagen y de como se vería la animación de los componentes.</p>
    <video-player class="espacio" src="video/pantallas partidas.mp4"/>

    
    
    
    
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
  .espacio 
    @apply mb-10 mt-10 
</style>