<template>
<div>
  <MainMenu/>
  <div class="caja">
    <h1>Estilo Tipográfico</h1>
    <p>Rubik fue diseñada por Philipp Hubert y Sebastian Fischer en Hubert & Fischer como parte del Chrome Cube Lab project. Es de licencia abierta, además incluye elementos OpenType.</p>
    <img class="rubik" src="img/Rubik.jpg" alt="">
    <h2>Rubik</h2>
    <p>La tipografía escogida para el sistema de diseño es Rubik, una sans serif con bordes levemente redondeados que la hacen singular y amable, dos  de nuestros valores.
    El estilo tipográfico debe ser aplicado usando los siguiente parámetros:
    </p>
    
    <h3>Pesos</h3>
    <p>En caso de titulares se debe usar el peso semiBold, sin embargo para subtitulares y texto corrido se debe usar el peso regular</p>
    <h3>Estilo</h3>
    <p>No se debe estirar, condensar,
    delinear o crear sombra paralela en ningún caso
    </p>
    <h3>Color</h3>
    <p>La tipografía se puede configurar en cualquiera de los colores definidos en la paleta bajo sus indicaciones correspondientes.</p>
    <h3>Alineación</h3>
    <p>Los textos deben estar alineados a la izquierda</p>
    <h3>Tamaños</h3>
    <p>La constante en la escala tipográfica es de un 
    incremento de 5 puntos (6,67 px).
    El tamaño más pequeño permitido es cinco
    puntos. Este tamaños solo debe usarse para aplicaciones en impresos.
    No hay límite de tamaño superior.

    Esta escala tipográfica de ejemplo utiliza Rubik para todos los titulares, cuerpo y subtítulos.
    La jerarquía se comunica a través de diferencias en el peso de la fuente (Bold,Semibold, Regular) y tamaño
    </p>
    <img class="tip" src="img/tamañostipo.jpg" alt="">
  </div>
</div>
  
</template>
<style lang="sass">
    .rubik
        @apply max-w-sm
        
    .tip
        @apply pb-20
</style>