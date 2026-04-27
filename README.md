# vskdev-vue-oneui

This project demonstrates the integration of the `vskdev-oneui-vue` component library into a Vue 3 application.

## Library Integration

The project uses the `vskdev-oneui-vue` library as a local package.

### How to use components

To use components from the library, import them and the required CSS in your Vue components:

```vue
<script setup>
import { Button } from 'vskdev-oneui-vue'
import 'vskdev-oneui-vue/dist/vskdev-oneui-vue.css'
</script>

<template>
  <Button variant="default">Click Me</Button>
</template>
```

## Changes Made

The following changes were implemented to set up the project and integrate the library:

1.  **Project Initialization**: Scaffolded a new Vue 3 project using `create-vue`.
2.  **Library Installation**: Linked the local library package in `package.json`:
    *   `"vskdev-oneui-vue": "file:../vskdev-oneui-vue"`
3.  **UI Implementation**: Updated `src/App.vue` to import the `Button` component and demonstration styles.
4.  **Linter Optimization**:
    *   Removed `oxlint` and its related configuration files (`.oxlintrc.json`).
    *   Updated `eslint.config.js` to rely solely on ESLint for linting.
    *   Simplified `npm run lint` script to run ESLint directly.
5.  **Code Formatting**: Configured Prettier and formatted the codebase.

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
# vskdev-vueweb-ui
