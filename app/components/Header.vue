<script setup lang="ts">

</script>

<template>
  <header class="bg-amber-800">
    <div class="mx-auto max-w-screen-xl px-4 sm:px-6 lg:px-8">
      <div class="flex h-16 items-center justify-between">
        <div class="flex-1 md:flex md:items-center md:gap-12">
          <NuxtLink to="/" class="block text-teal-600" href="#">
            <span class="sr-only">Home</span>
          </NuxtLink>
          <h1 class="font-medium text-white text-4xl italic"> Pamirian House</h1>
        </div>

        <div class="md:flex md:items-center md:gap-12">
          <nav aria-label="Global" class="hidden md:block">
            <ul class="flex items-center gap-6 text-sm">
              <li>
                <NuxtLink to="/" class="text-white transition hover:text-black" href="#"> About </NuxtLink>
              </li>

              <li>
                <NuxtLink to="/history" class="text-white transition hover:text-black" href="#"> History </NuxtLink>
              </li>

              <li>
                <NuxtLink to="/fwf" class="text-white transition hover:text-black" href="#"> Five Wooden Pillars </NuxtLink>
              </li>

              <li>
                <NuxtLink to="photos" class="text-white transition hover:text-black" href="#"> Photos </NuxtLink>
              </li>

              <li>
                <NuxtLink to="projects" class="text-white transition hover:text-black" href="#"> Projects </NuxtLink>
              </li>


            </ul>
          </nav>

          <div class="flex items-center gap-4">
            <div class="sm:flex sm:gap-4">


              <div class="hidden sm:flex">

              </div>
            </div>

            <div class="block md:hidden">
              <button class="rounded bg-black-100 p-2 text-black-600 transition hover:text-black-600/75">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>

</style>