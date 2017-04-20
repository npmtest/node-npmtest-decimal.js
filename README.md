# npmtest-decimal.js

#### basic test coverage for  decimal.js (v7.2.0)  [![npm package](https://img.shields.io/npm/v/npmtest-decimal.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-decimal.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-decimal.js.svg)](https://travis-ci.org/npmtest/node-npmtest-decimal.js)

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
    "name": "decimal.js",
    "description": "An arbitrary-precision Decimal type for JavaScript.",
    "version": "7.2.0",
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
    "repository": {
        "type": "git",
        "url": "https://github.com/MikeMcl/decimal.js.git"
    },
    "main": "decimal.js",
    "module": "decimal.es6.js",
    "author": {
        "name": "Michael Mclaughlin"
    },
    "license": "MIT",
    "scripts": {
        "test": "node ./test/test.js",
        "build": "uglifyjs decimal.js --source-map doc/decimal.js.map -c -m -o decimal.min.js --preamble \"/* decimal.js v7.2.0 https://github.com/MikeMcl/decimal.js/LICENCE */\""
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
