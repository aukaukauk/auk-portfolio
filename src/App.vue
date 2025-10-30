<template>
  <div>
    <header class="sticky top-0 z-40 backdrop-blur supports-[backdrop-filter]:bg-white/70 dark:supports-[backdrop-filter]:bg-neutral-950/60 border-b border-neutral-200 dark:border-neutral-800">
      <nav class="container-1080 h-16 flex items-center justify-between">
        <RouterLink to="/" class="font-medium tracking-tight">Your Name</RouterLink>
        <ul class="flex items-center gap-6 text-sm">
          <li><RouterLink to="/" class="hover:underline underline-offset-4">Home</RouterLink></li>
        </ul>
      </nav>
    </header>

    <main id="content" class="py-10 md:py-14">
      <RouterView />
    </main>

    <footer class="border-t border-neutral-200 dark:border-neutral-800 py-10 text-sm">
      <div class="container-1080 flex flex-col md:flex-row items-start md:items-center justify-between gap-4">
        <p class="text-neutral-500">© {{ year }} — Built with Vue + Tailwind</p>
        <a href="#" class="btn-link">Back to top ↑</a>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
const year = new Date().getFullYear()
</script>

<style scoped>
</style>
