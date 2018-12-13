# Workbox Unofficial CDN

[![automated](https://flat.badgen.net/badge/publish/automated/green)](#)
[![circle ci](https://flat.badgen.net/circleci/github/nuxtjs-community/workbox-cdn)](https://circleci.com/gh/nuxt-community/workbox-cdn)
[![npm version](https://flat.badgen.net/npm/v/@nuxtjs/workbox-cdn)](https://www.npmjs.com/package/@nuxtjs/workbox-cdn)
[![npm downloads](https://flat.badgen.net/npm/dt/@nuxtjs/workbox-cdn)](https://www.npmjs.com/package/@nuxtjs/workbox-cdn)
[![install size](https://flat.badgen.net/packagephobia/install/@nuxtjs/workbox-cdn)](https://packagephobia.now.sh/result?p=@nuxtjs/workbox-cdn)

[Workbox](https://developers.google.com/web/tools/workbox) Unofficial CDN and standalone NPM package.

## Why?

- Having public usage/download stats
- The `local` type costs `~8M` install size for `workbox-cli` package vs `< 1Mb` of this package
- Default workbox CDN is hosted on `storage.googleapis.com` which is sometimes unavailable

## Usage

**WIP**

Add a call to `workbox.setConfig({modulePathPrefix: '...'})` to your service worker to use these local libraries.

See https://goo.gl/Fo9gPX for further documentation.

## License

```
Copyright 2017 Google Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

CDN maintained by Nuxt.js Team
