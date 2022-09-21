<template>
  <div id="app">
    <div class="content">
      <router-view />
    </div>
  </div>
</template>
<script setup lang="ts"></script>
<style scoped>
#app {
  background-image: linear-gradient(to top, #5ee7df 0%, #b490ca 100%);
  padding: 16px 16px 50px;
  min-height: 100vh;
}

.content {
  max-width: 480px;
  margin: 0 auto;
}
</style>
