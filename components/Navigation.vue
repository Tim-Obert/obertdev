<template>
  <!-- Navbar -->
  <nav
    class="flex justify-between md:justify-around py-4 bg-white backdrop-blur-md shadow-md w-full px-10 fixed top-0 left-0 right-0 z-10 px-8 md:px-3">
    <!-- Logo Container -->
    <div class="flex items-center">
      <!-- Logo -->
      <a class="cursor-pointer">
        <h3 class="text-2xl font-medium text-blue-500">
          <img
            class="ml-2 h-14"
            src="obertDev2.png"
            alt="Store Logo"/>
        </h3>
      </a>
    </div>

    <!-- Links Section -->
    <div
      class="items-center md:space-x-8 justify-center justify-items-start md:justify-items-center md:flex md:pt-2 w-full left-0 top-16 px-5 md:px-10 py-3 md:py-0 border-t md:border-t-0">
      <NuxtLink to="/"
        class="flex text-gray-600 hover:text-primary cursor-pointer transition-colors duration-300">
        Home
      </NuxtLink>

      <NuxtLink to="/about"
        class="flex text-gray-600 hover:text-primary cursor-pointer transition-colors duration-300">
        About
      </NuxtLink>
    </div>

    <!-- Hamberger Menu -->
    <button
      class="w-10 h-10 md:hidden justify-self-end rounded-full hover:bg-gray-100">
      <svg
        class="mx-auto"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        version="1.1"
        width="24"
        height="24"
        viewBox="0 0 24 24">
        <path d="M3,6H21V8H3V6M3,11H21V13H3V11M3,16H21V18H3V16Z"/>
      </svg>
    </button>
  </nav>
</template>

<script>
export default {
  name: "Navigation"
}
</script>

<style>
.nuxt-link-exact-active {
  color: #f5a90a;
}
</style>

