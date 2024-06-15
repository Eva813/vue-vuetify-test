<template>
  <div class="about">
    <h1>This is an about page</h1>
    <v-date-input label="Select a date" prepend-icon="" prepend-inner-icon="$calendar" variant="solo"></v-date-input>
    <div>dwedwed</div>
  </div>
</template>
<script setup lang="ts">
const msg = 'Hello Vite + Vue 3 + TypeScript + VitePress!'
const foo = () => {
  console.log('foo')



  return 'foo'
}
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
