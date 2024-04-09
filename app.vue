<template>
  <div class="app">
    <!-- Your layout wrapper -->

    <header>
      <!-- Your header -->
    </header>
    <!-- Your page content (default is pages/index.vue) -->
    <NuxtPage />
    <footer>
      <!-- Your footer -->
    </footer>
  </div>
</template>

<script setup>
// Any script you might need
</script>

<style scoped>

#app{
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  width: 100vw;
  max-height: 100vh;
  margin: 0;
}

</style>