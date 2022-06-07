<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Paleta de Colores</h1>
    <h2>Paleta primaria</h2>
    <p>La paleta de color primaria  está compuesta de los mismos colores que coponen la marca con el objetivo de dar continuidad y unificación.
    Ambos son colores brillantes y vivos que resultan familiares al usuario por ser los mismos que los de la marca Telecinco.
    </p>
    <img class="colores" src="img/color-primario.jpg" alt="">
    <h3>Algunas recomendaciones de uso</h3>
    <p>El color azul escogido debe usarse en headings. Para un buen contraste debe usarse en texto sobre fondo blanco.
    Aunque el color blanco está pensado para usarse como fondo para la pastilla de rotulación principal, puede usarse en headings y en texto corrido pero siempre sobre fondos con oscuridad mínima del color azul primario.
    </p>
    
    <h2>Paleta secundaria</h2>
    <p>La paleta de color secundaria está compuesta de colores elegidos en función al color azul principal.</p>
    <h3>El azul oscuro</h3>
    <p>Es un 15% más oscuro que el original y es recomendable para textos pequeños sobre fondos de colores luminosos para conseguir una legibilidad mayor. Se usará para indicar elementos que son secundarios de cierto modo, como  el nombre del presentador, o presentadora, el lugar desde donde se retransmite o el nombre de sección en los intersticiales.
    </p>
    <h3>El azul claro</h3>
    <p> es un  15% más claro que el original y es recomendable para fondos, nunca debe usarse en headings y texto corrido si no es sobre fondos con el mínimo de oscuridad del azul oscuro definido anteriormente.
    Se usará para las pastillas secundarias que engloban los textos escritos en azul oscuro.
    </p>
    <h3>Complementario del color principal</h3>
    <p>Este color ha sido elegido para indicar ciertos elementos que necesitan llamar la atención por algún motivo,
    por ejemplo se usará para indicar el directo
    </p>
    <h3>Gris auxiliar </h3>
    <p>Este color ha sido pensado para ser usado en subtítulos y texto corrido sobre fondos claros.</p>
    <img class="colores" src="img/colores-sec.jpg" alt="">
  </div>
</div>
  
</template>
<style lang="sass">
  .colores
    @apply pb-24
  h3
    font-family: 'Rubik', sans-serif
    font-size: 13pt
    font-style: 500
    @apply pt-3 pb-3
  
</style>