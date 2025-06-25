<!--
 @name: index.vue
 @description: 应用 logo
 @author: 程序员优雅哥 youyacoder
 @time: 2025/4/17 13:27
-->
<template>
  <div class="wm-logo">
    <div class="logo">
      <img src="../../../assets/imgs/logo.png" />
    </div>
    <div class="name">WuMeng Admin</div>
  </div>
</template>

<script setup lang="ts"></script>
<style scoped lang="scss">
.wm-logo {
  @apply flex items-center w-[var(--wm-layout-sidebar-width)];

  .logo {
    @apply w-68px;

    img {
      @apply w-full;
    }
  }

  .name {
    @apply font-700 text-16px;
  }
}
</style>
