<template>
  <NConfigProvider :theme-overrides="theme">
    <NInput style="width: 33%; margin: 2rem" />
  </NConfigProvider>
</template>

<script setup>
import { NConfigProvider, NInput, NButton } from 'naive-ui';

const theme = {
  common: { primaryColor: "hsl(350deg 78% 56%)" }
};
</script>