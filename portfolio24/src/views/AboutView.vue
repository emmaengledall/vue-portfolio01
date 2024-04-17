<script setup> // Image import here <33
import imagePathAbout from '@/assets/pngFiles/scribble06.png';

</script>


<template>
<div class="bg-amber-100 w-screen h-screen grid grid-rows-3">

  <div class="absolute size-12/12 pt-20 opacity-60">
    <img :src="imagePathAbout" alt="woopss">
  </div>
  

  <div class="about font-AndaleMo pl-10 pt-20 flex flex-col text-sm z-10">
    <RouterLink to="/">// ABOUT</RouterLink> <!-- WORKS AS A ROUTERLINK TO HOMEPAGE-->
  </div>
   



<div class="font-AndaleMo pl-10 pt-20 flex flex-col justify-center z-10"> <!--MAIN TEXT ON ABOUT PAGE-->
  <h1 class="text-3xl">HI THERE, I'M EMMA-CHANTAL. </h1> 
  
  <p class="text-sm flex flex-col leading-loose">I’d consinder myself the following titles...frontend developer / website designer / coded designer <br>
Art and exploring my own creativity has always been a huge part of me. Drawing, painting, building and storytelling comes naturally. <br>
Being a creative person in a fast changing technogical world opens up a lot of possibilities. From 3D-modelling, coding, designing <br>
websites and combining design and data,</p>
</div>



</div>
</template>






<style>

</style>
