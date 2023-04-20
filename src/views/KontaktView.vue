<template>
<section class="bg-white">
  <div class="py-8 px-4 mx-auto max-w-screen-md sm:w-4/5">
      <h2 class="font-sans mb-4 text-2xl tracking-tight font-normal text-center text-gray-900 dark:text-black">Kontakt mig</h2>
      <p class="font-sans mb-2 font-light text-left text-black dark:text-black text-md text-justify sm:mb-5 lg:mb-16">Skal du have lavet hjemmeside, grafisk design eller have taget nogle fotos til din hjemmeside? Udfyld venligst formularen herunder, og jeg vil vende tilbage til dig hurtigst muligt.</p>
      <h2 class="font-sans mb-2 text-1xl tracking-tight font-normal text-left text-gray-900 dark:text-black">* Konktaktoplysninger</h2>
      <p class="font-sans mb-2 font-light text-left text-black dark:text-black text-sm sm:mb-10 lg:mb-16">Email: kristina.pagaard@gmail.com</p>
      <form action="#" class="space-y-8">
          <div>
              <label for="Navn" class="font-sans block mb-2 mt-0 text-sm font-medium text-black dark:text-black">Fornavn</label>
              <input type="Navn" id="email" class="shadow-sm bg-white border border-gray-300 text-gray-900 text-sm focus:ring-primary-500 focus:border-primary-500 block w-1/2 p-2.5 dark:border-gray-600 dark:placeholder-gray-400 dark:text-black dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="" required>
          </div>
          <div>
              <label for="Efternavn" class="font-sans block mb-2 text-sm font-medium text-black dark:text-black">Efternavn</label>
              <input type="Efternavn" id="email" class="shadow-sm bg-white border border-gray-300 text-gray-900 text-sm focus:ring-primary-500 focus:border-primary-500 block w-1/2 p-2.5 dark:border-gray-600 dark:placeholder-gray-400 dark:text-black dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="" required>
          </div>
          <div>
              <label for="email" class="font-sans block mb-2 text-sm font-medium text-black dark:text-black">Email</label>
              <input type="email" id="email" class="shadow-sm bg-white border border-gray-300 text-gray-900 text-sm focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:border-gray-600 dark:placeholder-gray-400 dark:text-black dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="" required>
          </div>
          <div>
              <label for="subject" class="font-sans block mb-2 text-sm font-medium text-black dark:text-black">Emne</label>
              <input type="text" id="subject" class="block p-3 w-full text-sm text-gray-900 bg-white border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500 dark:border-gray-600 dark:placeholder-gray-400 dark:text-black dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="" required>
          </div>
          <div class="sm:col-span-2">
              <label for="message" class="font-sans block mb-2 text-sm font-medium text-black dark:text-black">Besked</label>
              <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-white shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:border-gray-600 dark:placeholder-gray-400 dark:text-black dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder=""></textarea>
          </div>
          <button type="submit" class="font-sans bg-transparent hover:bg-black text-black font-semibold hover:text-white py-2 px-4 border border-black hover:border-transparent">Send besked</button>
      </form>
  </div>
</section>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>