<script setup lang="ts"></script>

<template>
  <div class="h-screen flex-col flex justify-center items-center">
    <div>
      <router-link to="/">home</router-link>
      <router-link to="/about">about</router-link>
    </div>
    <router-view />
  </div>
</template>
