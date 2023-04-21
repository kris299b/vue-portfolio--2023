<script setup>
import { RouterLink, RouterView} from 'vue-router'
</script>

<template>
  <header>
  <nav
    class="text-xs font-semibold relative flex w-full items-center justify-between bg-white text-black hover:text-black-800 focus:text-black :text-black flex-wrap justify-start"
    data-te-navbar-ref>
    <div class="px-4 lg:px-10 flex w-full flex-wrap items-center justify-between">
      <div
        class="items-center space-x-5 flex pr-0 m-0 md:!flex lg:!flex"
        id="navbarSupportedContentX"
        data-te-collapse-item>
        <RouterLink to="/">
        <img alt="Vue logo" class="logo" src="./assets/logo_done.png" width="60" height="60" />
        </RouterLink>
        <ul
          class="mr-auto flex flex-row sm:flex-row"
          data-te-navbar-nav-ref>
          <RouterLink to="/about">
          <li data-te-nav-item-ref>
            <a
              class="font-sans font-semibold ml-4 lg:ml-6 block transition duration-150 ease-in-out hover:text-black focus:text-neutral-700 disabled:text-black/30 dark:hover:text-grey dark:focus:text-black lg:p-2 [&.active]:text-black/90 link link-underline link-underline-black" 
              data-te-nav-link-ref
              data-te-ripple-init
              data-te-ripple-color="light"
              >OM</a
            >
          </li>
          </RouterLink>
          <RouterLink to="/Kontakt">
          <li data-te-nav-item-ref>
            <span
              class="font-sans font-semibold ml-4 lg:ml-6 block transition duration-150 ease-in-out hover:text-black focus:text-neutral-700 disabled:text-black/30 dark:hover:text-grey dark:focus:text-black lg:p-2 [&.active]:text-black/90 link link-underline link-underline-black"
              data-te-nav-link-ref
              data-te-ripple-init
              data-te-ripple-color="light"
              >KONTAKT</span
            >
          </li>
          </RouterLink>
          <li data-te-nav-item-ref>
            <a
              class="font-sans font-semibold ml-4 lg:ml-6 block transition duration-150 ease-in-out hover:text-black focus:text-neutral-700 disabled:text-black/30 dark:hover:text-grey dark:focus:text-black lg:p-2 [&.active]:text-black/90 link link-underline link-underline-black"
              href="/#port"
              data-te-nav-link-ref
              data-te-ripple-init
              data-te-ripple-color="light"
              >PORTFOLIO</a 
            >
          </li>
          <a href="https://www.linkedin.com/in/kristinapagaardhansen/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-3 w-3 lg:h-3 lg:w-3 mt-5 mr-6 lg:mr-14 absolute top-0 right-0"
            fill="currentColor"
            viewBox="0 0 24 24">
            <path
              d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.38 1.11-2.5 2.48-2.5s2.48 1.12 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.029-5.052 6.029 0v8.399h4.988v-10.131c0-7.88-8.922-7.593-11.018-3.714v-2.155z" />
          </svg>
          </a>
        </ul>
      </div>
    </div>
  </nav>
</header>
  <RouterView></RouterView>




<footer
  class="bg-white text-center bg-stone-500">
  <div class="p-4 text-center text-black dark:text-black">
    © 2023 All Rights Reserved:
    <a
      class="text-neutral-800 dark:text-black"
      href="https://tailwind-elements.com/"
      >Kristina P. Hansen</a
    >
  </div>
</footer>



</template>




<style scoped>

.link-underline {
		border-bottom-width: 0;
		background-image: linear-gradient(transparent, transparent), linear-gradient(#fff, #fff);
		background-size: 0 2px;
		background-position: 0 100%;
		background-repeat: no-repeat;
		transition: background-size .3s ease-in-out;
	}

	.link-underline-black {
		background-image: linear-gradient(transparent, transparent), linear-gradient(rgb(74, 74, 74), rgb(74, 74, 74))
	}

	.link-underline:hover {
		background-size: 100% 2px;
		background-position: 0 100%
	}

</style>
