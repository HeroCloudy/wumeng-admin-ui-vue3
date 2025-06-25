<!--
 @name: wm-layout-sidebar.vue
 @description: 布局左侧组件
 @author: 程序员优雅哥 youyacoder
 @time: 2025/6/21 11:24
-->
<template>
  <div class="wm-layout-sidebar">wm-layout-sidebar</div>
</template>

<script setup lang="ts">
defineProps<{
  p?: string
}>()
</script>
<style scoped lang="scss">
.wm-layout-sidebar {
  @apply w-[var(--wm-sidebar-width-default)] bg-white;
  box-shadow: 2px 0 1px 0 rgba(0, 0, 0, 0.1);
}
</style>
