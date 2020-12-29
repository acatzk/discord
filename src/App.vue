<template>
  <!-- main flex -->
  <div id="app" class="flex flex-col min-h-screen">
    <!-- first col -->
    <div class="bg-blue-300 flex">
      <div class="bg-red-300 w-56 flex-none">Tailwind CSS</div>
      <div>Rest of top bar</div>
    </div>
    <!-- second col -->
    <div class="bg-green-300 flex-1 flex">
      <div class="bg-pink-200 w-56 flex-none">hastag sidebar</div>
      <div class="bg-blue-100 flex-1 flex justify-between">
        <div class="bg-green-100 flex-1">main content</div>
        <div class="flex-none w-56 bg-yellow-100">sidebar</div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'app',
    props: {},
    components: {},
    data () {
      return {}
    }
  }
</script>
