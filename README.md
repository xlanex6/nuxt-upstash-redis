<!--
Get your module up and running quickly.

Find and replace all on all files (CMD+SHIFT+F):
- Name: Nuxt upstash-redis
- Package name: nuxt-upstash-redis
- Description: Nuxt module to connect and use @upstash/redis from your fullstack app
-->

# Nuxt upstash-redis


[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

Nuxt module to connect and use @upstash/redis from your Nuxt fullstack app for doing amazing things.

- [✨ &nbsp;Release Notes](/CHANGELOG.md)
<!-- - [🏀 Online playground](https://stackblitz.com/github/your-org/nuxt-upstash-redis?file=playground%2Fapp.vue) -->
<!-- - [📖 &nbsp;Documentation](https://example.com) -->

## Features

<!-- Highlight some of the features your module provide here -->
- 🚀 Use @upstash/redis in your Nuxt app
- 🔐 &nbsp;Securely connect to your Upstash Redis instance
- 📦 &nbsp;Use Upstash Redis for caching, storing sessions, and more
- 📖 &nbsp;TypeScript support
- 🎉 &nbsp;...and more!


## Quick Setup

1. Add `nuxt-upstash-redis` dependency to your project

```bash
# Using pnpm
pnpm add -D nuxt-upstash-redis

# Using yarn
yarn add --dev nuxt-upstash-redis

# Using npm
npm install --save-dev nuxt-upstash-redis
```

2. Add `nuxt-upstash-redis` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    'nuxt-upstash-redis'
  ]
})
```

That's it! You can now use Nuxt upstash-redis in your Nuxt app ✨

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
[npm-version-src]: https://img.shields.io/npm/v/nuxt-upstash-redis/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/nuxt-upstash-redis

[npm-downloads-src]: https://img.shields.io/npm/dm/nuxt-upstash-redis.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/nuxt-upstash-redis

[license-src]: https://img.shields.io/npm/l/nuxt-upstash-redis.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/nuxt-upstash-redis

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
