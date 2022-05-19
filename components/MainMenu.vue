<template>
  <div class="side-bar">
    <div class="logo"><LogoMenu/></div>
    <div class="said-main">
      <ul class="main">
        <li class="visible" id="cero">
          Brad Aparience
        </li>
        <li class="visible" id="open" >
          Basic
          <ul>
            <li class="invisible">Circle</li>
            <li class="invisible">Colours</li>
            <li class="invisible">Typography</li>
            <li class="invisible">Layout Structure</li>
            <li class="invisible">Imagery</li>
            <li class="invisible">Animation</li>
          </ul>
        </li>
        <li class="visible" >User Interface</li>
        <li class="visible">Communication Media</li>
        <li class="visible">Corporate Branding</li>
        <li class="visible">Motion pictures</li>

      </ul>
    </div>


  </div>
</template>

<style lang="sass">
  //fuentes
    @import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;500&display=swap');
  .side-bar
    background-color: #135a9a
    width: 40vh
    height: 100vh
    ul 
      font-family: 'Rubik', sans-serif
      font-size: 12pt
      font-style: 500
      color: white
      li
        font-family: 'Rubik', sans-serif
        font-size: 12pt
        font-style: 500
        color: white
        @apply ml-11 mt-8
        &:hover
          color: #12a4d9
          cursor: pointer
  #cero
    margin-top: 0
  #open
    .invisible
      display: none
      


</style>
