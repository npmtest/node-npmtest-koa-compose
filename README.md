# npmtest-koa-compose

#### test coverage for  [koa-compose (v4.0.0)](https://github.com/koajs/compose#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-compose.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-compose) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-compose.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-compose)

#### compose Koa middleware

[![NPM](https://nodei.co/npm/koa-compose.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-compose)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-compose/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-compose/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-compose/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-compose/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-compose/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-compose/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-compose/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-compose/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-compose/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-compose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-compose/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-compose/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-compose/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-compose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-compose/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-compose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-compose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/koajs/compose/issues"
    },
    "dependencies": {},
    "description": "compose Koa middleware",
    "devDependencies": {
        "istanbul": "^0.4.2",
        "matcha": "^0.7.0",
        "mocha": "^3.1.2",
        "should": "^2.0.0",
        "standard": "^9.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2800a513d9c361ef0d63852b038e4f6f2d5a773c",
        "tarball": "https://registry.npmjs.org/koa-compose/-/koa-compose-4.0.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "8684618343159bdc12e254483e3f51ee444078b0",
    "homepage": "https://github.com/koajs/compose#readme",
    "keywords": [
        "koa",
        "middleware",
        "compose"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "stephenmathieson"
        },
        {
            "name": "tejasmanohar"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "koa-compose",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/compose.git"
    },
    "scripts": {
        "bench": "matcha bench/bench.js",
        "lint": "standard index.js test/*.js",
        "test": "mocha --require should --reporter spec",
        "test-cov": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
