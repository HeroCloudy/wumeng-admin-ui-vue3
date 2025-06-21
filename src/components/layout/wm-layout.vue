<!--
 @name: wm-layout.vue
 @description: 布局组件
 @author: 程序员优雅哥 youyacoder
 @time: 2025/6/21 11:24
-->
<template>
  <div class="wm-layout">wm-layout</div>
</template>

<script setup lang="ts">
defineProps<{
  p?: string
}>()
</script>
<style scoped lang="scss">
.wm-layout {
  @apply bg-gray;
}
</style>
