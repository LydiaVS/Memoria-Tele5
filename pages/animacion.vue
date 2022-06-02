<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Animación</h1>
    <div>
     <!-- <video :src="require('../assets/video/logo.mp4')" width="640" height="480"></video> --> 
     <video-player src="video/logo.mp4"/>
    </div>

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
  video
    width: 640px
    height: 480px
  
</style>