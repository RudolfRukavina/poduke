<template>
  <nav class="bg-white">
    <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl p-4">
      <NuxtLink :to="{ path: '/', hash: '#naslovnica' }" class="flex items-center space-x-3 rtl:space-x-reverse">
        <h1
          class="text-2xl font-extrabold tracking-tight leading-none text-black drop-shadow-xl [text-shadow:_0_4px_0_rgb(0_0_0_/_10%)] lg:text-4xl">
          Poduke Parallel
        </h1>
      </NuxtLink>
      <div class="flex items-center space-x-6 rtl:space-x-reverse">
        <a href="tel:+385917865619"
          class="text-3xl px-3 rounded-xl text-black bg-gray-100 hover:bg-gray-200 hover:shadow-sm"><i
            class="fa fa-phone"></i></a>
      </div>
    </div>
  </nav>
  <nav class="bg-gray-50 shadow-xl overflow-x-auto text-nowrap whitespace-nowrap px-5">
    <div class="max-w-screen-xl px-4 py-3 mx-auto">
      <div class="flex items-center">
        <ul class="flex flex-row font-medium mt-0 space-x-8 rtl:space-x-reverse text-sm">
          <li>
            <NuxtLink :to="{ path: '/', hash: '#naslovnica' }" class="text-gray-900 hover:underline">Naslovnica
            </NuxtLink>
          </li>
          <li>
            <NuxtLink :to="{ path: '/', hash: '#usluge' }" class="text-gray-900 hover:underline">Usluge
            </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/onama" class="text-gray-900 hover:underline">O nama
            </NuxtLink>
          </li>
          <li>
            <button id="dropdownNavbarLinkKontakt" data-dropdown-toggle="dropdownNavbarKontakt"
              class="flex items-center justify-between w-full text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:hover:bg-gray-700 md:dark:hover:bg-transparent pe-5">
              Kontakt

              <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                viewBox="0 0 10 6">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="m1 1 4 4 4-4" />
              </svg>
            </button>

            <div id="dropdownNavbarKontakt"
              class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700 dark:divide-gray-600">
              <ul class="py-2 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownLargeButton">
                <li>
                  <a href="mailto:parallel.upiti@gmail.com"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i
                      class="fa fa-envelope"> Pošaljite e-mail!</i></a>
                </li>
                <li>
                  <a href="https://maps.app.goo.gl/9dFa9f6sUkVuHxRD9" target="_blank"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i
                      class="fa fa-map-marker"> Riva 20, Rijeka</i></a>
                </li>
                <li>
                  <a href="tel:+385917865619"
                    class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i
                      class="fa fa-phone"> +385917865619</i></a>
                </li>
              </ul>
              <div class="py-1">
                <a href="https://www.facebook.com/poduke.parallel" target="_blank"
                  class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"><i
                    class="fa fa-facebook">acebook</i></a>
                <a href="https://www.instagram.com/poduke.parallel" target="_blank"
                  class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white"><i
                    class="fa fa-instagram"> Instragram</i></a>
              </div>
              <div class="py-1">
                <NuxtLink :to="{ path: '/', hash: '#radnovrijeme' }"
                  class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white">
                  <i class="fa fa-calendar"> Radno vrijeme</i>
                </NuxtLink>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script setup>
  import { onMounted } from "vue";
  import {
    initAccordions,
    initCarousels,
    initCollapses,
    initDials,
    initDismisses,
    initDrawers,
    initDropdowns,
    initModals,
    initPopovers,
    initTabs,
    initTooltips,
  } from "flowbite";

  // initialize components based on data attribute selectors
  onMounted(() => {
    initAccordions();
    initCarousels();
    initCollapses();
    initDials();
    initDismisses();
    initDrawers();
    initDropdowns();
    initModals();
    initPopovers();
    initTabs();
    initTooltips();
  });
</script>

<style scoped>
.router-link-exact-active {
  color: rgb(28, 28, 28);
  font-weight: 600;
}
</style>
