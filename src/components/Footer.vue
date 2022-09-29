<script lang="ts" setup>
import { useDark } from "@vueuse/core";
const isDark = useDark();
</script>

<template>
  <div>
    <button @click="isDark = !isDark">{{ isDark ? "黑" : "白" }}</button>
  </div>
</template>
