<template>
  <main>
  <div class="relative overflow-hidden bg-cover bg-no-repeat">
    <div class="absolute top-0 right-0 bottom-0 left-0 h-full w-full overflow-hidden bg-fixed">
      <div class="sm:flex h-full sm:items-center ml-10">
        <div class="bg-white bg-opacity-40 sm:bg-white sm:bg-opacity-40 text-left sm:p-2 md:p-10 md:bg-white md:bg-opacity-40">
          <h1 class="hidden md:block font-sans sm:text-4xl lg:text-7xl text-black pb-5">KRISTINA</h1>
          <p class="hidden md:block font-sans text-sm font-normal pb-5">WEB | GRAFISK DESIGN | FOTO</p>
          <button type="button" class="hidden md:block font-sans bg-slate-800 hover:bg-black text-white font-normal py-2 px-4">
            <RouterLink to="/Kontakt">KONTAKT</RouterLink>
          </button>
        </div>
      </div>
    </div>
    <img class="image" src="../assets/Heroimg_done.jpg" alt="">
  </div>

  
<div id="port" class="flex justify-center p-10 flex-col sm:flex-col sm:ml-20 sm:pt-0 md:pt-5 md:flex-row md:ml-0 lg:flex-row">
  <div
    class="block max-w-sm bg-white white:bg-neutral-700 m-4">
    <a href="#!" data-te-ripple-init data-te-ripple-color="light">
      <img
        class="web"
        src="../assets/web.jpg"
        alt="" />
    </a>
    <div class="p-6">
      <h5
        class="text-center mb-2 text-lg font-medium leading-tight text-neutral-800 black:text-neutral-50 sm:flex-col">
        WEB
      </h5>
      <div class="font-sans flex justify-center pt-3">
        <button class="bg-transparent hover:bg-black text-black font-normal hover:text-white py-2 px-4 border border-black hover:border-transparent sm:mb-5 ">
          <RouterLink to="/portfolio">SE MERE</RouterLink>
        </button>
      </div>
    </div>
  </div>
  <div
    class="block max-w-sm bg-white white:bg-neutral-700 m-4">
    <a href="#!" data-te-ripple-init data-te-ripple-color="light">
      <img
        class="grafisk design"
        src="../assets/cream_graphicdesign.jpg"
        alt="" />
    </a>
    <div class="p-6">
      <h5
        class="text-center mb-2 text-lg font-medium leading-tight text-neutral-800 black:text-neutral-50">
        GRAFISK DESIGN 
      </h5>
      <div class="font-sans flex justify-center pt-3">
        <button class="bg-transparent hover:bg-black text-black font-normal hover:text-white py-2 px-4 border border-black hover:border-transparent sm:mb-5">
          <RouterLink to="/GrafiskDesign">SE MERE</RouterLink>
        </button>
      </div>
    </div>
  </div>
  <div
    class="block max-w-sm bg-white white:bg-neutral-700 m-4">
    <a href="#!" data-te-ripple-init data-te-ripple-color="light">
      <img
        class="foto"
        src="../assets/stephanie_copy.jpg"
        alt="" />
    </a>
    <div class="p-6">
      <h5
        class="text-center mb-2 text-lg font-medium leading-tight text-neutral-800 black:text-neutral-50">
        FOTO
      </h5>
      <div class="font-sans flex justify-center pt-3">
        <button class="bg-transparent hover:bg-black text-black font-normal hover:text-white py-2 px-4 border border-black hover:border-transparent">
          <RouterLink to="/Foto">SE MERE</RouterLink>
        </button>
      </div>
    </div>
  </div>
</div>
  </main>
</template>


<script setup>
import { RouterLink, RouterView} from 'vue-router'
</script>
