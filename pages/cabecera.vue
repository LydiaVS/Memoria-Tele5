<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Cabecera</h1>
    <p>Telecinco engloba información de muchas localizaciones (puntos geográficos que cambian) y se focaliza en ellas . <br>
    Hacemos referencia a las distintas localizaciones desde las que se transmiten. <br>
    noticias cambiantes, unidas por líneas que las conectan (representadas por el gráfico)
    </p>
    <h3>Keyvisual</h3>
   <img class="key" src="img/keyvisual.jpg" alt="">
   <h2>Animación de cabecera</h2>
    <video-player class="cabecera" src="video/cabecera.mp4"/>
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
  .key
     @apply max-w-3xl pb-5 pt-12
  .cabecera
    @apply mb-12

</style>