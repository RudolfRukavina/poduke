<template>
  <ClientOnly>
    <footer class="bg-white">
      <div class="container mx-auto px-8">
        <div class="w-full flex flex-col md:flex-row py-6">
          <div class="flex-1 mb-6 text-black">
            <a class="text-pink-600 no-underline hover:no-underline font-bold text-2xl lg:text-4xl" href="#">
              <img src="../assets/logo.jpeg" alt=""
                class="h-14 w-14 rounded shadow-xl inline-block me-3 ring-1 ring-primary/5" />
            </a>
          </div>
          <div class="flex-1">
            <p class="uppercase text-gray-500 md:mb-6">Parallel poduke</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/', hash: '#naslovnica' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Naslovnica
                </NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/', hash: '#usluge' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Usluge</NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/onama', hash: '#naslovnica' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">O nama</NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/', hash: '#radnovrijeme' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Radno vrijeme</NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <a href="https://maps.app.goo.gl/9dFa9f6sUkVuHxRD9" target="_blank"
                  class="hover:underline text-gray-800 underline hover:text-pink-500">Riva 20, Rijeka</a>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="uppercase text-gray-500 md:mb-6">
              Pripreme za državnu maturu
            </p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/pripreme', hash: '#cjenik' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Cjenik
                </NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/pripreme', hash: '#mojplanzamaturu' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Kalkulator</NuxtLink>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="uppercase text-gray-500 md:mb-6">Instrukcije</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/instrukcije', hash: '#osnovnaskola' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Osnovna škola
                </NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/instrukcije', hash: '#srednjaskola' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Srednja škola</NuxtLink>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <NuxtLink :to="{ path: '/instrukcije', hash: '#fakultet' }"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Fakultet</NuxtLink>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="uppercase text-gray-500 md:mb-6">Mreže</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <a href="https://www.facebook.com/poduke.parallel" target="_blank"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Facebook</a>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <a href="https://www.instagram.com/poduke.parallel" target="_blank"
                  class="no-underline hover:underline text-gray-800 hover:text-pink-500">Instagram</a>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="uppercase text-gray-500 md:mb-6">Prava korisnika</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <a href="#" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Uvjeti korištenja</a>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <a href="#" class="no-underline hover:underline text-gray-800 hover:text-pink-500">Privatnost</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </ClientOnly>
</template>
