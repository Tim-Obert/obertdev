<template>
  <div>
    <Navigation/>
    <main class="flex flex-col items-center justify-center mt-20">
      <Nuxt/>
    </main>
  </div>
</template>
<script>
import Navigation from "../components/Navigation";

export default {
  components: {Navigation}
}
</script>
