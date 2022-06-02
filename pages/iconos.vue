<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Iconos</h1>
    <p>Los iconos del sistema se construyen a partir de la combinación de las segmentaciones definidas anteriormente combinandolas como un puzzle.
    Los iconos están destinados a las animaciones intersticiales pero pueden usarse en otros casos si se da la opción.
    <br>
    Para fomentar su accesibilidad, es recomendable que los iconos vayan acompañados de texto alternativo.
    </p>
    <div class="flex">
      <img class="iconos"  src="../assets/img/iconos.jpg" alt="">
      <img class="icono2"  src="../assets/img/icono2.jpg" alt="">

    </div>

    <h2>Ejemplo de aniamción del icono</h2>
    <video-player src="video/deportes circ 2.mp4"/>
  </div>
</div>
  
</template>

<script>
import VideoPlayer from 'nuxt-video-player'

export default{
components: {
    VideoPlayer
}

}
</script>
<style lang="sass">
  .flex
    display: flex
  .iconos
    @apply  max-w-md  
  .icono2
    @apply max-w-xs 
    
</style>