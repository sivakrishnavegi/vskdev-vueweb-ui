<script setup>
import { Button } from 'vskdev-oneui-vue'
</script>

<template>
  <div class="container">
    <h1>Vskdev Web</h1>
    <p>Using vskdev-oneui-vue library</p>

    <div class="demo-section">
      <Button variant="default">Default Button</Button>
      <Button variant="destructive">Destructive Button</Button>
      <Button variant="outline">Outline Button</Button>
      <Button variant="secondary">Secondary Button</Button>
      <Button variant="ghost">Ghost Button</Button>
      <Button variant="link">Link Button</Button>
    </div>
  </div>
</template>

<style scoped>
.container {
  padding: 2rem;
  font-family: sans-serif;
}
.demo-section {
  display: flex;
  gap: 1rem;
  margin-top: 2rem;
  flex-wrap: wrap;
}
</style>
