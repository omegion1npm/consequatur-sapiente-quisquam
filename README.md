# @omegion1npm/consequatur-sapiente-quisquam [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Meet%20this%20awesome%20library&url=https://github.com/omegion1npm/consequatur-sapiente-quisquam&via=nicolasvanhoren&hashtags=javascript,asyncawait,async,libraries,programming)

![logo](https://github.com/omegion1npm/consequatur-sapiente-quisquam/raw/master/img/facebook_cover_photo_2_680.png)

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/@omegion1npm/consequatur-sapiente-quisquam?style=social)](https://github.com/omegion1npm/consequatur-sapiente-quisquam/stargazers) [![Website](https://img.shields.io/website.svg?url=http%3A%2F%2Fnicolas-van.github.io%2F@omegion1npm/consequatur-sapiente-quisquam)](https://nicolas-van.github.io/@omegion1npm/consequatur-sapiente-quisquam)
[![Node.js CI](https://github.com/omegion1npm/consequatur-sapiente-quisquam/workflows/Node.js%20CI/badge.svg)](https://github.com/omegion1npm/consequatur-sapiente-quisquam/actions) [![npm](https://img.shields.io/npm/v/@omegion1npm/consequatur-sapiente-quisquam)](https://www.npmjs.com/package/@omegion1npm/consequatur-sapiente-quisquam) [![Coverage Status](https://coveralls.io/repos/github/nicolas-van/@omegion1npm/consequatur-sapiente-quisquam/badge.svg?branch=master)](https://coveralls.io/github/nicolas-van/@omegion1npm/consequatur-sapiente-quisquam?branch=master) [![](https://data.jsdelivr.com/v1/package/npm/@omegion1npm/consequatur-sapiente-quisquam/badge)](https://www.jsdelivr.com/package/npm/@omegion1npm/consequatur-sapiente-quisquam)

A modern JavaScript tooling library for asynchronous operations using async/await, promises and async generators.

This library is a modernized alternative to a lot of libraries like [Async.js](https://caolan.github.io/async/v3/) that were created using the legacy callback style to handle asynchronous operations. Its goal is to be as complete as any of those libraries while being built from the very beginning with async/await and promises in mind.

[See the documentation](https://nicolas-van.github.io/@omegion1npm/consequatur-sapiente-quisquam).

* Exclusively uses async/await, promises and async generators in its code, tests and documentation.
* Has low bundle size.
* Has 100% code coverage.
* Bundled for ESM modules, CommonJS and UMD.
* Works in node >= 8 and in the vast majority of browsers (very old browser compatibility can be achieved using Babel and shims).
* Has Typescript support.

[![Stargazers repo roster for @nicolas-van/@omegion1npm/consequatur-sapiente-quisquam](https://reporoster.com/stars/nicolas-van/@omegion1npm/consequatur-sapiente-quisquam)](https://github.com/omegion1npm/consequatur-sapiente-quisquam/stargazers)

## Installation

```bash
npm install --save @omegion1npm/consequatur-sapiente-quisquam
```

Or use [jsDelivr](https://www.jsdelivr.com/package/npm/@omegion1npm/consequatur-sapiente-quisquam) to get the UMD version. The content of the library will be available under the `modernAsync` global variable.

## Usage

```javascript
import { asyncMap, asyncSleep } from '@omegion1npm/consequatur-sapiente-quisquam'

const array = [1, 2, 3]
const result = await asyncMap(array, async (v) => {
  await asyncSleep(10)
  return v * 2
})
console.log(result)
```

[See the documentation for the rest](https://nicolas-van.github.io/@omegion1npm/consequatur-sapiente-quisquam).

## Migrating from version 1.X to version 2.X

[See the migration guide](https://github.com/omegion1npm/consequatur-sapiente-quisquam/blob/master/version-1-to-2-guide.md).

## Changelog

[The changelog](https://github.com/omegion1npm/consequatur-sapiente-quisquam/blob/master/CHANGELOG.md).

## Contribution Guide

[The contribution guide](https://github.com/omegion1npm/consequatur-sapiente-quisquam/blob/master/CONTRIBUTING.md)

## License

[The license](https://github.com/omegion1npm/consequatur-sapiente-quisquam/blob/master/LICENSE.md).
