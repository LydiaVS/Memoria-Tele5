<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Cortinillas</h1>
    <p>En cuanto a las cortinillas o intersticiales, traeremos los iconos establecidos en la identidad visual del programa para poder realizar pequeñas animaciones de no más de 2 segundos con las que entrarían los programas como el tiempo y los deportes. <br>
    Está animación estaría basada en las propia del logo.</p>
    <h2>Intersticiales</h2>
    <video-player class="cabecera" src="video/intersticial_tiempo.mp4"/>
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