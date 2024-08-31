<template>
  <div class="wrap">
    <TheHeader />
    <main class="main">メイン</main>
    <TheFooter />
  </div>
</template>

<script setup lang="ts">
import TheHeader from 'src/components/TheHeader.vue'
import TheFooter from 'src/components/TheFooter.vue'
</script>

<style scoped>
.wrap {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 90vh;
  background-color: aqua;
}

.main {
  flex: 1;
  padding: 15px;
}
</style>
