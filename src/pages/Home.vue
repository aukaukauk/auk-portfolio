<template>
  <div class="space-y-20 md:space-y-28">
    <!-- Hero -->
    <section class="container-1080 grid md:grid-cols-2 gap-10 items-center">

      <div class="justify-self-center md:order-2">
        <div >
          <img class="w-64 h-64 md:w-96 md:h-96 rounded-xl object-cover" src="@/assets/images/auk.png" alt="some_text">
        </div>
      </div>

      
      <div class="space-y-6">
        <h1>你好，我是海雀</h1>
        <p class="text-neutral-600 dark:text-neutral-400 max-w-prose">
               湾区认知科学学生，全栈开发者。喜欢创造与构建东西。相信数字与物理世界同等真实，并将愈发重要。
        </p>

        <div class="flex flex-wrap gap-2">
          <span class="tag">科技乐观</span>
          <span class="tag">CogSci</span>
          <span class="tag">HCI</span>
          <span class="tag">XR/VR</span>
          <span class="tag">空间计算</span>
          <span class="tag">FPV飞手</span>
        </div>

        <div class="flex flex-wrap items-center gap-x-6 gap-y-3 pt-1 text-sm font-mono text-neutral-600 dark:text-neutral-400">
          <div>心率 <span class="text-neutral-900 dark:text-neutral-100">78</span> bpm</div>
          <div>状态 清醒</div>
          <div>更新于 2m 前</div>
        </div>

        <div class="flex items-center gap-6 pt-2">
          <RouterLink to="/portfolio" class="btn-link">查看作品集 →</RouterLink>
          <a href="mailto:you@example.com" class="btn-link">联系我 →</a>
        </div>
      </div>


    </section>

    <!-- About preview -->
    <section class="container-1080 space-y-6">
      <header>
        <h2>About / 关于我</h2>
      </header>
      <div class="grid md:grid-cols-3 gap-8 items-start">
        <p class="md:col-span-2 text-neutral-700 dark:text-neutral-300 max-w-prose">
          占位符
        </p>
        <div class="self-start">
          <RouterLink to="/about" class="btn-link">详细了解 →</RouterLink>
        </div>
      </div>
    </section>

   
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
</style>
