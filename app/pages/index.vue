<script setup lang="ts">

</script>

<template>
  <!-- https://gist.github.com/goodreds/3d044027175954984fb96c7407a955ab -->

  <!-- Container -->
  <div class="relative flex flex-col items-center mx-auto lg:flex-row-reverse lg:max-w-5xl lg:mt-12 xl:max-w-6xl">

    <!-- Image Column -->
    <div class="w-full h-64 lg:w-1/2 lg:h-auto">
      <img class="h-full w-full object-cover" src="/images/image2.jpg" alt="Winding mountain road">
    </div>
    <!-- Close Image Column -->

    <!-- Text Column -->
    <div
        class="max-w-lg bg-white md:max-w-2xl md:z-10 md:shadow-lg md:absolute md:top-0 md:mt-48 lg:w-3/5 lg:left-0 lg:mt-20 lg:ml-20 xl:mt-24 xl:ml-12">
      <!-- Text Wrapper -->
      <div class="flex flex-col p-12 md:px-16">
        <h2 class="text-4xl font-bold uppercase text-amber-700 lg:text-4xl">About my special house</h2>
        <p class="mt-4">
          The Pamiri house is seen as a representation of the cosmos. The layered roof, with its central opening, symbolizes the heavens and the connection between the physical and spiritual worlds.
          The house, particularly with its five pillars, is considered a sacred dwelling, reflecting ancient Zoroastrian beliefs (fire, elements) blended with Ismaili Islamic spiritual traditions.
        </p>
        <!-- Button Container -->
        <div class="mt-8">
          <NuxtLink to="/about"
             class="inline-block w-full text-center text-lg font-medium text-gray-100 bg-amber-700 border-solid border-2 border-amber-700 py-4 px-10 hover:bg-amber-700 hover:shadow-md md:w-48">Read
            More</NuxtLink>
        </div>
      </div>
      <!-- Close Text Wrapper -->
    </div>
    <!-- Close Text Column -->

  </div>
  <div class="flex flex-wrap justify-center mt-10">

    <!-- card 1 -->
    <div class="p-4 max-w-sm">
      <div class="flex rounded-lg h-full dark:bg-gray-800 bg-amber-800 p-8 flex-col">
        <div class="flex items-center mb-3">
          <div
              class="w-8 h-8 mr-3 inline-flex items-center justify-center rounded-full bg-amber-700 text-white flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
              <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
            </svg>
          </div>
          <h2 class="text-white dark:text-white text-lg font-medium">The stepped roof(Chorkhona)</h2>
        </div>
        <div class="flex flex-col justify-between flex-grow">
          <p class="leading-relaxed text-base text-white dark:text-gray-300">

            *   This is the most iconic and recognizable feature. The roof is not flat but consists of five concentric square tiers/layers, built from wooden beams, gradually diminishing in size as they rise.
          </p>
          <a href="#" class="mt-3 text-black dark:text-white hover:text-blue-600 inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>

    <!-- card 2 -->
    <div class="p-4 max-w-sm">
      <div class="flex rounded-lg h-full dark:bg-amber-800 bg-amber-800 p-8 flex-col">
        <div class="flex items-center mb-3">
          <div
              class="w-8 h-8 mr-3 inline-flex items-center justify-center rounded-full dark:bg-amber-700 bg-amber-700 text-white flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
              <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
            </svg>
          </div>
          <h2 class="text-white dark:text-white text-lg font-medium">Function</h2>
        </div>
        <div class="flex flex-col justify-between flex-grow">
          <p class="leading-relaxed text-base text-white dark:text-gray-300">
            The Tuvdon allows natural light to enter the otherwise dimly lit interior and provides ventilation for smoke from the central hearth. The multi-layered design traps heat efficiently.
          </p>
          <a href="#" class="mt-3 text-black dark:text-white hover:text-white inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>

    <!-- card 3 -->
    <div class="p-4 max-w-sm">
      <div class="flex rounded-lg h-full dark:bg-amber-700 bg-amber-800 p-8 flex-col">
        <div class="flex items-center mb-3">
          <div
              class="w-8 h-8 mr-3 inline-flex items-center justify-center rounded-full dark:bg-amber-700 bg-amber-700 text-white flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
              <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
            </svg>
          </div>
          <h2 class="text-white dark:text-white text-lg font-medium">Materials</h2>
        </div>
        <div class="flex flex-col justify-between flex-grow">
          <p class="leading-relaxed text-base text-white dark:text-gray-300">
            * Traditionally constructed from readily available local materials.Provide excellent thermal mass, acting as natural insulation against extreme temperatures.
          </p>
          <a href="#" class="mt-3 text-black dark:text-white hover:text-white inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                 stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>

  </div>
  <div class="relative flex flex-col items-center max-w-screen-xl  px-4 mx-auto md:flex-row sm:px-6 p-8">
    <div class="flex items-center   md:pb-20 md:pt-10 md:pr-10">
      <div class="text-left">
        <h2
            class="text-4xl font-extrabold leading-10 tracking-tight text-black sm:text-5xl sm:leading-none md:text-6xl">
          Unique
          <span class="font-bold text-amber-900">Identity</span>
          <span class="text-xl font-semibold rounded-full text-blueGray-500">2.0</span>
        </h2>
        <p class="max-w-md mx-auto mt-3 text-base text- sm:text-lg md:mt-5 md:text-xl md:max-w-4xl">
          Unlike the majority of Tajiks, who speak a dialect of Persian, Pamiris speak several distinct East Iranian Pamiri languages (like Shughni, Wakhi, Ishkashimi, Rushani). These languages are not simply dialects; they are separate linguistic branches, adding to their unique cultural identity.
        </p>
        <div class="mt-5 sm:flex md:mt-8">
          <div class="rounded-md shadow"><a href=""
                                            class="flex items-center justify-center w-full px-8 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-amber-900 border border-transparent rounded-md hover:bg-amber-600 focus:outline-none focus:shadow-outline-blue md:py-4 md:text-lg md:px-10">
            Getting started
          </a></div>
          <div class="mt-3 rounded-md shadow sm:mt-0 sm:ml-3">
            <a href=""
               class="flex items-center justify-center w-full px-8 py-3 text-base font-medium leading-6 text-amber-900 transition duration-150 ease-in-out bg-white border border-transparent rounded-md hover:text-amber-600 focus:outline-none focus:shadow-outline-blue md:py-4 md:text-lg md:px-10">
              Contribute
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>


  <div class="bg-amber dark:bg-amber flex justify-center items-center w-screen  -mt-1-">
    <div class="border shadow-amber shadow-md max-w-2xl p-6 rounded-lg dark:bg-gray-700 dark:text-amber-750">
      <h1 class="text-5xl font-bold font-extrabold py-3 text-amber-900">Three facts about Pamirian house</h1>
      <ul class="list-disc text-lg px-6 text-500">
        <li> Built for Super Cold: It has super thick walls (made of stone, mud, and wood) and a special roof design that keeps it very warm inside, even when it's freezing cold in the mountains..</li>
        <li> Roof is a Stepped Pyramid: The roof isn't flat! It has five square "steps" going up, like a small pyramid. At the top, there's a hole that lets in light and lets out smoke..</li>
        <li>Five Special Pillars: Inside, there are five important wooden pillars that hold up the roof. These pillars are very meaningful to the people who live there, representing their spiritual beliefs..</li>
      </ul>
    </div>
  </div>

</template>

<style scoped>

</style>
