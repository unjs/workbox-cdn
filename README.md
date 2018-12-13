# Workbox Unofficial CDN

[![automated](https://flat.badgen.net/badge/publish/automated/green)](#)
[![circle ci](https://flat.badgen.net/circleci/github/nuxt-community/workbox-cdn)](https://circleci.com/gh/nuxt-community/workbox-cdn)
[![npm version](https://flat.badgen.net/npm/v/workbox-cdn)](https://www.npmjs.com/package/workbox-cdn)
[![npm downloads](https://flat.badgen.net/npm/dt/workbox-cdn)](https://www.npmjs.com/package/workbox-cdn)
[![install size](https://flat.badgen.net/packagephobia/install/workbox-cdn)](https://packagephobia.now.sh/result?p=workbox-cdn)

[Workbox](https://developers.google.com/web/tools/workbox) Unofficial CDN and standalone NPM package.

## Why?

- Having public usage/download stats
- The `local` type costs `~8M` install size for `workbox-cli` package vs `< 1Mb` of this package
- Default workbox CDN is hosted on `storage.googleapis.com` which is sometimes unavailable

## Usage

Add a call to `workbox.setConfig({modulePathPrefix: '...'})` to your service worker to use hosted workbox libraries.

See https://goo.gl/Fo9gPX for further documentation.

You have two options:

### Option 1: UNPKG

Use `https://unpkg.com/workbox-cdn@^3.0.0/workbox`

### Option 2: NPM Package

Install `workbox-cdn` package with `yarn add workbox-cdn` or `npm i workbox-cdn` and integrate it with your own build system or serve contents of `workbox` dir

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
