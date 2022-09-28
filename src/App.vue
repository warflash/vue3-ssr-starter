<template>
  <div>{{ m }}</div>
</template>

<script setup>
const newLocale = 'en';
const messages = await import(`./locales/${newLocale}.json`);
const m = messages.default;
</script>