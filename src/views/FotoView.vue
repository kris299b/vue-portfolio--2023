<template>
<div id="port" class="flex justify-center p-10">
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
        class="text-center mb-2 text-lg font-medium leading-tight text-neutral-800 black:text-neutral-50 sm:">
        PORTRÆT
      </h5>
      <div class="flex justify-center pt-3">
        <button class="bg-transparent hover:bg-black text-black font-normal hover:text-white py-2 px-4 border border-black hover:border-transparent">
          <RouterLink to="/Portrait">SE MERE</RouterLink>
        </button>
      </div>
    </div>
  </div>
  <div
    class="block max-w-sm bg-white white:bg-neutral-700 m-4">
    <a href="#!" data-te-ripple-init data-te-ripple-color="light">
      <img
        class="foto"
        src="../assets/produkt1_forside.jpg"
        alt="" />
    </a>
    <div class="p-6">
      <h5
        class="text-center mb-2 text-lg font-medium leading-tight text-neutral-800 black:text-neutral-50:">
        PRODUKTER
      </h5>
      <div class="flex justify-center pt-3">
        <button class="bg-transparent hover:bg-black text-black font-normal hover:text-white py-2 px-4 border border-black hover:border-transparent">
          <RouterLink to="/Produkter">SE MERE</RouterLink>
        </button>
      </div>
    </div>
  </div>
</div>


</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>