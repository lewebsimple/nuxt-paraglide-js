# Nuxt Paraglide JS

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

Translate your project using this Paraglide JS module for Nuxt.

- [✨ &nbsp;Release Notes](/CHANGELOG.md)

## Quick Setup

1. Add `nuxt-paraglide-js` dependency to your project

```bash
# Using pnpm
pnpm add -D nuxt-paraglide-js

# Using yarn
yarn add --dev nuxt-paraglide-js

# Using npm
npm install --save-dev nuxt-paraglide-js
```

2. Add `nuxt-paraglide-js` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    'nuxt-paraglide-js'
  ]
})
```

That's it! You can now use Nuxt Paraglide JS in your Nuxt app ✨

## Development

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-paraglide-js/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/nuxt-paraglide-js

[npm-downloads-src]: https://img.shields.io/npm/dm/nuxt-paraglide-js.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/nuxt-paraglide-js

[license-src]: https://img.shields.io/npm/l/nuxt-paraglide-js.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/nuxt-paraglide-js

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
