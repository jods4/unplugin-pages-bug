<script setup>
import { routes } from 'vue-router/auto/routes'
</script>

<template>
  <main>
    <div v-for="r of routes">
      <div v-for="(value, key) of r.meta">
        <b>{{ key }}</b> = {{ value }}
      </div>
    </div>
  </main>
</template>