<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup lang="ts">
  const lessonStore = useLessonStore()
  onMounted(() => {
    lessonStore.fetchLessons()
  })
</script>