<script setup>
import './assets/css/main.scss';

useSeoMeta({
  title: 'Project-A',
  ogTitle: 'Project-A',
  description: 'The Project-A site',
  ogDescription: 'The Project-A site',
})
</script>

<template>
  <main>
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </main>
</template>
