<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Elementos móviles</h1>
    <p> En cuanto a los elementos móviles del sistema de TeleCinco tenemos la animación de los diferentes inconos mencionados con anterioridad en el apartado de marca. ya que estos son extraidos del circulo de la marca.
      <br> Es por ello que en este apartado haremos meción a la animación del directo que sería una gif que se manterdría en la pantalla durante la transmisión.Este pequeño elemento consta de varios circulos también extraidos de la marca, haciendo alusión a un parpadeo de luz de una cámara grabando. <br>
      Para llamar la atención sobre los demás elementos de la pantalla el color que emplearíamos sería el naranja, uno de la paleta de secundaría de colores.
    </p>
    <h2>Animación de elemento</h2>
    <video-player src="video/Directo.mp4"/>
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