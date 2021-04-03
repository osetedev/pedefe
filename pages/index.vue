<template>
  <div class="container m-auto flex text-center justify-center items-center min-h-screen">
    <div>
      <img src="~/assets/images/pdf.svg" class="w-40 inline" />
      <h1 class="text-8xl py-4 font-light">pedefe</h1>
      <div class="links">
        <NuxtLink
          to="/merge"
          class="transition-colors duration-500 ease-in-out inline-block px-4 py-2 rounded-md bg-green-100 text-green-700 hover:bg-green-200"
        >
          Merge
        </NuxtLink>
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="transition-colors duration-500 ease-in-out inline-block px-4 py-2 rounded-md bg-blue-100 text-blue-700 hover:bg-blue-200"
        >
          Reorder
        </a>
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="transition-colors duration-500 ease-in-out inline-block px-4 py-2 rounded-md bg-red-100 text-red-700 hover:bg-red-200"
        >
          Compress
        </a>
      </div>
      <div class="pt-5 text-gray-400">Iconos diseñados por <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.es/" title="Flaticon">www.flaticon.es</a></div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
