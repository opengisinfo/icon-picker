# icon-picker

[![NPM version](https://img.shields.io/npm/v/@opengis/icon-picker?style=plain)](https://www.npmjs.com/package/@opengis/icon-picker)

Component for icon selection

Includes a versatile collection of pre-styled Tailwind CSS icons.

## Documentation

Complete documentation and examples available at [https://icon-picker.opengis.info](https://icon-picker.opengis.info)

- [Component documentation](https://icon-picker.opengis.info/guide/)

## Changelog

Full change log available at [https://icon-picker.opengis.info/changelog/](https://icon-picker.opengis.info/changelog/)


## Install & Usage

### 1. Install the package
```bash
npm i @opengis/icon-picker
```
### 2. Register the component
```typescript
// main.ts or main.js
import { createApp } from 'vue'
import App from './App.vue'
import IconPicker from '@opengis/icon-picker'

createApp(App).component('IconPicker', IconPicker).mount('#app')

```
### 3. Use it in your template
```vue
<template>
  <IconPicker
    v-model="selectedIcon"
    :icons-list="myIcons"
    width="500"
  />
</template>

<script setup lang="ts">
import { ref } from 'vue'

const selectedIcon = ref('')
const myIcons = ['home', 'user', 'settings', 'arrow-left', 'check'] // your SVG names
</script>
```

---

## Contributions
We welcome contributions!
Feel free to open issues, suggest features, or submit pull requests.

## Licence

MIT
