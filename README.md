React & 6to5 client-server isomorphic project template
====================

[![Licence](http://img.shields.io/badge/license-MIT-000000.svg?style=flat-square)](https://npmjs.org/package/flow-6to5-isomorphic-kameita)
[![Version](http://img.shields.io/npm/v/flow-6to5-isomorphic-kameita.svg?style=flat-square)](https://npmjs.org/package/flow-6to5-isomorphic-kameita)

亀板 ( _Kameita_ ) は陶芸、ろくろの道具です。粘土をのせたりします。

## Getting Started

```
git clone https://github.com/ahomu/flow-t6o5-isomorphic-kameita.git ./your-project
cd ./your-project
rm -rf .git
npm install
```

## ES6 Compatibility

This template is dependent on [6to5/6to5](https://github.com/6to5/6to5). Please see [6to5's document site](https://6to5.org/). 

[Optional Runtime](https://6to5.org/optional-runtime.html) and [Polyfill](https://6to5.org/polyfill.html) are already supported.

### Convert the es6 files into es5 compat files, and browserifying

```
npm run build
```

### Build & bump version in package.json

```
npm run release
```

### Run tests for development (auto re-run when file changed)

```
npm run devel
```

### Run tests for ci

```
npm test
# or npm run test
```

### for Node modules

Initial setting is for browser, please following steps if you want to use in the Node module.

1. Remove the comment in Gulpfile.js, to set for node setting.
2. `testem.node.json` rename to `testem.json`
3. Add `import  * as assert from 'power-assert';` into test code.

## Using libraries

- [facebook/react](https://github.com/facebook/react)
- [6to5/6to5](https://github.com/6to5/6to5)
- [substack/node-browserify](https://github.com/substack/node-browserify)
- [gulpjs/gulp](https://github.com/gulpjs/gulp/)
- [airportyh/testem](https://github.com/airportyh/testem)
- [mochajs/mocha](https://github.com/mochajs/mocha)
- [twada/power-assert](https://github.com/twada/power-assert)
- [cjohansen/Sinon.JS](https://github.com/cjohansen/Sinon.JS)

## ToDo

- register [Gemnasium](https://gemnasium.com/)
- add CI service configuration (Travis, Circle, etc)
- add coverage reporter
- add code quality reporter
