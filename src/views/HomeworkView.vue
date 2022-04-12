<script setup lang="ts">
import HomeworkTask from '@/components/HomeworkTask.vue'
</script>

<template>
  <div class="about">
    <h1>This is homework view</h1>
    <HomeworkTask>
    </HomeworkTask>
  </div>

</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
    place-content: center;
    place-items: center;
  }
}
</style>