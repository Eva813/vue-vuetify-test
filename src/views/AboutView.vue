<template>
  <div class="about">
    <h1>This is an about page</h1>
    <v-date-input label="Select a date" prepend-icon="" prepend-inner-icon="$calendar" variant="solo"></v-date-input>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
