<div align="center"><img src="browserify.png" alt="Browserify!"></div>

# Awesome Browserify with stars

> :crystal\_ball: A curated list of awesome [Browserify](https://github.com/substack/node-browserify) ⭐ 14,697 | 🐛 382 | 🌐 JavaScript | 📅 2024-12-21 resources, libraries, and tools.

Please help improve this list by [contributing](contributing.md)!

## Contents

* [About](#about)
* [Official Resources](#official-resources)
* [Community Resources](#community-resources)
* [Tutorials](#tutorials)
* [Articles](#articles)
* [Demos](#demos)
* [Videos](#videos)
* [Tools](#tools)
  * [Development Servers](#development-servers)
  * [Plugins](#plugins)
  * [Watchers](#watchers)
  * [CSS Bundlers](#css-bundlers)
  * [Transforms](#transforms)
  * [Node in the Browser](#node-in-the-browser)
  * [Production Tools](#production-tools)

## About

Browserify lets you `require('modules')` in the browser by bundling up all of your dependencies.

You can use a node-style `require()` to organize your browser code and load modules installed by npm. Browserify will recursively analyze all the `require()` calls in your app in order to build a bundle you can serve up to the browser in a single `<script>` tag.

## Official Resources

* [Docs](https://github.com/substack/node-browserify#usage) ⭐ 14,697 | 🐛 382 | 🌐 JavaScript | 📅 2024-12-21
* [Repo](https://github.com/substack/node-browserify) ⭐ 14,697 | 🐛 382 | 🌐 JavaScript | 📅 2024-12-21
* [Handbook](https://github.com/substack/browserify-handbook) ⭐ 4,591 | 🐛 19 | 🌐 JavaScript | 📅 2024-12-21
* [Website](http://browserify.org/)

## Community Resources

* [IRC](http://webchat.freenode.net/?channels=browserify)
* [Twitter](http://twitter.com/browserify)
* [StackOverflow](http://stackoverflow.com/questions/tagged/browserify)

## Tutorials

* [Hello World with Browserify](http://browserify.org/#middle-section)
* [Browserify Adventure](https://github.com/workshopper/browserify-adventure) ⭐ 143 | 🐛 12 | 🌐 JavaScript | 📅 2016-06-20
* [A Gentle Browserify Walkthrough](https://ponyfoo.com/articles/a-gentle-browserify-walkthrough)
* [Browserify guide](http://zhaoda.net/2015/10/16/browserify-guide/) (Chinese)

## Articles

* [Introduction to Browserify](https://writingjavascript.org/posts/introduction-to-browserify)
* [Using npm on the client side](http://dontkry.com/posts/code/using-npm-on-the-client-side.html)
* [How Browserify Works](http://benclinkinbeard.com/posts/how-browserify-works/)
* [Gulp + Browserify: The Everything Post](https://www.viget.com/articles/gulp-browserify-starter-faq)
* [Browserify vs Component](http://www.forbeslindesay.co.uk/post/44144487088/browserify-vs-component)
* [Browserify for Webpack users](https://gist.github.com/substack/68f8d502be42d5cd4942)
* [Browserify vs. Webpack](https://mattdesl.svbtle.com/browserify-vs-webpack)

## Demos

* [Canvas Splitter](http://requirebin.com/?gist=maxogden/9576799) by [hughsk](http://github.com/hughsk)
* [Infinite 2D Cave Generator](http://requirebin.com/?gist=maxogden/9557700) by [hughsk](http://github.com/hughsk)
* [2D Velocity Control](http://requirebin.com/?gist=maxogden/9557776) by [sethvincent](http://github.com/sethvincent)

## Videos

* [James Halliday (substack) - LXJS 2013 - Modularidade para todos](https://www.youtube.com/watch?v=DCQNm6yiZh0)
* [Getting Started with Browserify](https://www.youtube.com/watch?v=CTAa8IcQh1U) by [shama](https://github.com/shama/)
* [Transform your Bundles with Browserify](https://www.youtube.com/watch?v=Uk2bgp8OLT8) by [shama](https://github.com/shama/)

## Tools

### Development Servers

* [budo](https://github.com/mattdesl/budo) ⭐ 2,169 | 🐛 41 | 🌐 JavaScript | 📅 2022-08-30 - Dev server for rapid prototyping.
* [beefy](https://github.com/chrisdickinson/beefy) ⭐ 796 | 🐛 46 | 🌐 JavaScript | 📅 2017-09-25 - Local development server that aims to make using browserify fast and fun.
* [wzrd](https://github.com/maxogden/wzrd) ⭐ 249 | 🐛 7 | 🌐 JavaScript | 📅 2020-09-04 - Super minimal browserify development server.

### Plugins

* [browserify-hmr](https://github.com/AgentME/browserify-hmr) ⭐ 372 | 🐛 24 | 🌐 JavaScript | 📅 2023-01-04 - Hot Module Replacement plugin for Browserify.

### Watchers

* [watchify](https://github.com/substack/watchify) ⭐ 1,785 | 🐛 37 | 🌐 JavaScript | 📅 2024-12-21 - Watch mode for browserify builds.
* [persistify](https://github.com/royriojas/persistify) ⭐ 77 | 🐛 2 | 🌐 JavaScript | 📅 2023-12-18 - Wrapper around `browserify` to make incremental builds.

### CSS bundlers

* [sheetify](https://github.com/stackcss/sheetify) ⭐ 445 | 🐛 18 | 🌐 JavaScript | 📅 2020-09-19 - Modular CSS bundler for browserify.
* [css-modulesify](https://github.com/css-modules/css-modulesify) ⭐ 402 | 🐛 30 | 🌐 JavaScript | 📅 2019-11-02 - Browserify plugin to load CSS Modules.
* [parcelify](https://github.com/rotundasoftware/parcelify) ⭐ 250 | 🐛 11 | 🌐 JavaScript | 📅 2020-02-24 - Add css to your npm modules consumed with browserify.

### Transforms

* [babelify](https://github.com/babel/babelify) ⭐ 1,677 | 🐛 12 | 🌐 JavaScript | 📅 2021-08-06 - Browserify transform for babel.
* [brfs](https://github.com/substack/brfs) ⭐ 556 | 🐛 23 | 🌐 JavaScript | 📅 2024-12-21 - `fs.readFileSync()` and `fs.readFile()` static asset browserify transform.
* [aliasify](https://github.com/benbria/aliasify) ⭐ 203 | 🐛 11 | 🌐 CoffeeScript | 📅 2016-12-01 - Remap require calls at build time.

### Node in the Browser

* [buffer](https://github.com/feross/buffer) ⭐ 1,891 | 🐛 57 | 🌐 JavaScript | 📅 2025-10-28 - The `buffer` module from node.js, for the browser.
* [stream-browserify](https://github.com/substack/stream-browserify) ⭐ 105 | 🐛 6 | 🌐 JavaScript | 📅 2024-12-21 - The `stream` module from node core, for browsers!
* [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - Port of node's `crypto` module to the browser.
* [requirebin](http://requirebin.com/) - Write browser JavaScript programs using modules from NPM.

### Production Tools

* [bankai](https://github.com/yoshuawuyts/bankai) ⭐ 1,084 | 🐛 55 | 🌐 JavaScript | 📅 2022-05-19 - DIY asset server. Serves HTML, CSS and JS as streams.
* [wzrd.in](https://wzrd.in/) - Browserify CDN. Browserify-as-a-Service!

## Contributing

Contributions welcome! Please read the [contributing guidelines](contributing.md) before getting started.

## License

The [browserify logo](browserify.png) is by [substack](https://github.com/substack).

All other content is released to the public domain under [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html).

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
