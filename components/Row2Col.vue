<template>
  <div class="row-element grid lg:grid-cols-2 grid-cols-1 min-h-screen">
    <div class="circle1 w-full flex items-center justify-center">
      <div class="circle2 xl:m-52 lg:m-24 sm:m-44 sm:mb-0 rounded-full p-2 sm:bg-gray-100 flex items-center justify-center overflow-hidden">
      <div class="circle3 rounded-full p-2 sm:bg-gray-200 overflow-hidden">
        <div class="bg-primary rounded-full overflow-hidden">
          <img src="tim-obert.png">
        </div>
      </div>
      </div>
    </div>
    <div class="flex items-center justify-start">
      <div class="lg:p-52 p-10 lg:pl-3">
        <h1 class="text-6xl font-extrabold">Hey ich bin</h1>
        <h1 class="text-6xl font-extrabold pl-20"><span class="text-primary">Tim</span> Obert</h1>
        <h2 class="text-2xl pt-2">Web Developer</h2>
        <p class="font-mono pt-5">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Row2Col",
  mounted() {
    this.animations()
  },
  methods: {
    animations(){
      let tl = this.$gsap.timeline()
    }
  }

}
</script>

