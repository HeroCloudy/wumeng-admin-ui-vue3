<!--
 @name: wm-layout-header.vue
 @description: 布局顶部组件
 @author: 程序员优雅哥 youyacoder
 @time: 2025/6/21 11:23
-->
<template>
  <header class="wm-layout-header">
    <wm-layout-logo />

    <div class="flex-1"></div>
  </header>
</template>

<script setup lang="ts">
defineProps<{
  p?: string
}>()
</script>
<style scoped>
.wm-layout-header {
  @apply h-[var(--wm-layout-header-height)] bg-white flex items-center justify-center px-20px;
  box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.1);
}
</style>
