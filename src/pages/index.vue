<template>
  <div class="h-50%">
    <hello-world msg="message" />
    <p v-for="i in 100" :key="i">Hello World {{ i }}</p>
  </div>
</template>

<script setup lang="ts"></script>
