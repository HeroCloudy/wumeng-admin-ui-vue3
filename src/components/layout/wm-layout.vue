<!--
 @name: wm-layout.vue
 @description: 布局组件
 @author: 程序员优雅哥 youyacoder
 @time: 2025/6/21 11:24
-->
<template>
  <div class="wm-layout">
    <wm-layout-header></wm-layout-header>
    <div class="wm-rest">
      <wm-layout-sidebar></wm-layout-sidebar>

      <div class="wm-main">
        <div class="wm-main-wrapper">
          <el-scrollbar height="100%">
            <router-view></router-view>
          </el-scrollbar>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  p?: string
}>()
</script>
<style scoped lang="scss">
.wm-layout {
  @apply h-screen overflow-hidden flex flex-col bg-[var(--wm-bg)];

  .wm-rest {
    @apply flex-1 overflow-hidden flex mt-1px;

    .wm-main {
      @apply flex-1 overflow-hidden;

      &-wrapper {
        @apply h-full w-full;
      }
    }
  }
}
</style>
