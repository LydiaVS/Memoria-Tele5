<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Introducción</h1>
    <p> Telecinco es una cadena de televisión español en abierto de carácter privado comercial, cuyo pilar básico son la información y el entretenimiento, este pertenece a una empresa llamada 
      Mediaset que se dedica a desarrollar diferentes cadenas de televisión.
    </p>
    <img class="mediaset" src="../assets/img/Mediaset_cadenas.png" alt="Mediaset Cadenas">
    <p>
      Estos canales tratan de diversos temas y cada uno con su público objetivo y marca diferente. Pero la nueva imagen corporativa, realizada por la agencia Summa, ha aunado la esencia, por un lado, el nuevo logotipo comparte la tipografía Gill Sans Itálica con la marca original italiana.  Por otro lado, al conjunto se han incorporado la parte superior del característico número “5” de Telecinco como parte de la “ñ” de España y al final se ha incluido la esfera que comparten todos los canales del grupo, 
      favoreciendo la función de la nueva identidad corporativa como marca paraguas.
    </p>
    <img src="../assets/img/Summa_logo.jpg" alt="">
    <p>Por lo que respecta al color, el nuevo logotipo presenta el gris de Mediaset junto al azul de Telecinco como color corporativo secundario. El resultado es una combinación potente y diferenciadora, donde ambas palabras adquieren protagonismo.
      <br>
      Esto es algo que no vemos reflejado en el logo de los informativos del programa, siguen manteniendo el color azul como primario pero 
    </p>
  </div>
</div>
  
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style lang="sass">

  .caja 
    position: absolute
    margin-left: 50vh
    h1
      font-family: 'Rubik', sans-serif
      font-size: 40pt
      font-weight: 500
      @apply pt-14 pb-3
    p 
      font-family: 'Rubik', sans-serif
      font-size: 12pt
      font-weight: 300
      @apply text-gray-500 pr-28 pb-3
    .mediaset
      @apply max-w-xl
    
    
</style>