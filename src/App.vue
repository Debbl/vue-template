<script setup lang="ts"></script>

<template>
  <div class="flex h-screen flex-col items-center justify-center">
    <div>
      <router-link to="/">home</router-link>
      <router-link to="/about">about</router-link>
    </div>
    <router-view />
  </div>
</template>
