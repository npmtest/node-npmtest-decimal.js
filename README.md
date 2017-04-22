# npmtest-decimal.js

#### basic test coverage for  [decimal.js (v7.2.0)](https://github.com/MikeMcl/decimal.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-decimal.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-decimal.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-decimal.js.svg)](https://travis-ci.org/npmtest/node-npmtest-decimal.js)

#### An arbitrary-precision Decimal type for JavaScript.

[![NPM](https://nodei.co/npm/decimal.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/decimal.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-decimal.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-decimal.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-decimal.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-decimal.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-decimal.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-decimal.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-decimal.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-decimal.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-decimal.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-decimal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-decimal.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-decimal.js/build/test-report.html](https://npmtest.github.io/node-npmtest-decimal.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-decimal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-decimal.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-decimal.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-decimal.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Mclaughlin"
    },
    "bugs": {
        "url": "https://github.com/MikeMcl/decimal.js/issues"
    },
    "dependencies": {},
    "description": "An arbitrary-precision Decimal type for JavaScript.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "abb95d934f527664256ba213087f013f3cdc4fdf",
        "tarball": "https://registry.npmjs.org/decimal.js/-/decimal.js-7.2.0.tgz"
    },
    "gitHead": "2be14dfdd74a8b992c58999824efc9abd58240ad",
    "homepage": "https://github.com/MikeMcl/decimal.js#readme",
    "keywords": [
        "arbitrary",
        "precision",
        "arithmetic",
        "big",
        "number",
        "decimal",
        "float",
        "biginteger",
        "bigdecimal",
        "bignumber",
        "bigint",
        "bignum"
    ],
    "license": "MIT",
    "main": "decimal.js",
    "maintainers": [
        {
            "name": "mikemcl"
        }
    ],
    "module": "decimal.es6.js",
    "name": "decimal.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MikeMcl/decimal.js.git"
    },
    "scripts": {
        "build": "uglifyjs decimal.js --source-map doc/decimal.js.map -c -m -o decimal.min.js --preamble \"/* decimal.js v7.2.0 https://github.com/MikeMcl/decimal.js/LICENCE */\"",
        "test": "node ./test/test.js"
    },
    "version": "7.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
