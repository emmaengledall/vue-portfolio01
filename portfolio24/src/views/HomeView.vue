<script setup> // FIRST IMPORT IMG. FILES INTO THE SCRIPT PART - SECOND BRING IT INTO YOUR DIVS
  import imagePath1 from '@/assets/pngFiles/scribble01.png'; // IMG. IMPORT HERE <33
  import imagePath2 from '@/assets/pngFiles/scribble03.png'; 
  import imagePath3 from '@/assets/pngFiles/scribble04.png'; 
  import imagePath4 from '@/assets/pngFiles/scribble05.png'; 

  import imagePathAbout from '@/assets/pngFiles/scribble06.png';
  import imagePathPortfolio from '@/assets/pngFiles/scribble07.png';
  import imagePathContact from '@/assets/pngFiles/scribble08.png';

</script>

<template>
    <div >
      
  <div class="text-sm absolute wrapper bg-amber-100 font-AndaleMo w-screen h-screen grid grid-cols-2 grid-rows-3"> <!-- DIV FOR ONLY ROUTERLINK STYLE-->
    
      <div class=""> <!-- HOMEPAGE BUTTON/LOGO?? -->
        <RouterLink to="/"></RouterLink> 
      </div>
          
      <div class="relative row-start-1 pl-14 flex flex-col justify-center pt-5"> <!-- ABOUT LINK PÅ HOMEPAGE -->
        <RouterLink to="/about" >// ABOUT</RouterLink>
        <div class="size-9/12 pl-14">
          <img :src="imagePathAbout" alt="woopss"></div> 
      </div>
      
      <div class="relative row-start-2 pl-14 flex flex-col justify-center pt-5"> <!-- PORTFOLIOOOOOOOO LINK PÅ HOMEPAGE -->
        <RouterLink to="/portfolio">// PORTFOLIO</RouterLink>
        <div class="size-9/12 pl-14"><img :src="imagePathPortfolio" alt="wooops2"></div>
      </div>

      <div class="relative row-start-3 text-start pl-14 flex flex-col justify-center pt-5"> <!-- CONTACT LINK PÅ HOMEPAGE -->
        <RouterLink to="/contact">// CONTACT</RouterLink>
        <div class="size-9/12 pl-14"><img :src="imagePathContact" alt="wooops3"></div>
      </div>

      <div class="relative leading-loose row-start-3 flex-col justify-center pt-10 pl-36" > <!-- WELCOME TEXT ON WEBSITE-->
        <h1 class="text-sm"> EMMA-CHANTAL ENGLEDALL</h1>
          <p class="text-sm">
              frontend developer / website designer / coded designer <br><br>
              technical designer with passion for design and appearance. <br>
              currently studying visuel communication with focus on programming <br>
              at the Dansih school of media and journalism. </p>
      </div>


    </div>
      
  </div>
 <!-- <div>
  <div class="home">
    <h1>The ultimate homepage</h1>
  </div>

</div> -->
</template>
