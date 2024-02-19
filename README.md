## On-demand components auto importing for Vuesax Alpha.

[![NPM version](https://img.shields.io/npm/v/@vuesax-alpha/auto-import-resolver?color=a1b858&label=)](https://www.npmjs.com/package/@vuesax-alpha/auto-import-resolver)

### Use

```ts
// vite.config.js
import Components from 'unplugin-vue-components/vite'
import { VuesaxAlphaResolver } from '@vuesax-alpha/auto-import-resolver'

// your plugin installation
Components({
  resolvers: [VuesaxAlphaResolver()]
})
```
