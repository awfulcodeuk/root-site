<script setup lang="ts">

</script>

<template>
  <div>
    <nav class="bg-gray-100">
      <div class="container mx-auto px-6 py-2 flex justify-between items-center">
        <a class="font-bold text-2xl lg:text-4xl" href="#">
          AwfulCode
        </a>
        <div class="block lg:hidden">
          <button class="flex items-center px-3 py-2 border rounded text-gray-500 border-gray-600 hover:text-gray-800 hover:border-teal-500 appearance-none focus:outline-none">
            <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <title>Menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
            </svg>
          </button>
        </div>
        <div class="hidden lg:block">
          <ul class="inline-flex">
            <li>
              <NuxtLink class="px-4 hover:text-gray-800" to="/">
                Home
              </NuxtLink>
            </li>
            <li>
              <NuxtLink class="px-4 hover:text-gray-800" to="/about">
                About
              </NuxtLink>
            </li>
            <li>
              <NuxtLink class="px-4 hover:text-gray-800" to="/contact">
                Contact
              </NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>

</style>
