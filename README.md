# foot-date

![Node](https://img.shields.io/node/v/foot-date.svg?style=flat-square)
[![NPM](https://img.shields.io/npm/v/foot-date.svg?style=flat-square)](https://www.npmjs.com/package/foot-date)
[![Travis](https://img.shields.io/travis/footanalytics/foot-date/master.svg?style=flat-square)](https://travis-ci.org/footanalytics/foot-date)
[![David](https://img.shields.io/david/footanalytics/foot-date.svg?style=flat-square)](https://david-dm.org/footanalytics/foot-date)
[![Coverage Status](https://img.shields.io/coveralls/footanalytics/foot-date.svg?style=flat-square)](https://coveralls.io/github/footanalytics/foot-date)
[![NPM](https://img.shields.io/npm/dt/foot-date.svg?style=flat-square)](https://www.npmjs.com/package/foot-date)

> Foot Analytics Date utilities

### Usage

```js
import footDate from 'foot-date';

```

### Installation

Install via [yarn](https://github.com/yarnpkg/yarn)

	yarn add foot-date (--dev)

or npm

	npm install foot-date (--save-dev)


### configuration

You can pass in extra options as a configuration object (➕ required, ➖ optional, ✏️ default).

```js
import footDate from 'foot-date';

```

➖ **property** ( type ) ` ✏️ default `
<br/> 📝 description
<br/> ❗️ warning
<br/> ℹ️ info
<br/> 💡 example

### methods

#### #name

```js
footDate

```

### Examples

See [`example`](example/script.js) folder or the [runkit](https://runkit.com/footanalytics/foot-date) example.

### Builds

If you don't use a package manager, you can [access `foot-date` via unpkg (CDN)](https://unpkg.com/foot-date/), download the source, or point your package manager to the url.

`foot-date` is compiled as a collection of [CommonJS](http://webpack.github.io/docs/commonjs.html) modules & [ES2015 modules](http://www.2ality.com/2014/0
  -9/es6-modules-final.html) for bundlers that support the `jsnext:main` or `module` field in package.json (Rollup, Webpack 2)

The `foot-date` package includes precompiled production and development [UMD](https://github.com/umdjs/umd) builds in the [`dist/umd` folder](https://unpkg.com/foot-date/dist/umd/). They can be used directly without a bundler and are thus compatible with many popular JavaScript module loaders and environments. You can drop a UMD build as a [`<script>` tag](https://unpkg.com/foot-date) on your page. The UMD builds make `foot-date` available as a `window.footDate` global variable.

### License

The code is available under the [MIT](LICENSE) license.

### Contributing

We are open to contributions, see [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

### Misc

This module was created using [generator-module-boilerplate](https://github.com/duivvv/generator-module-boilerplate).
