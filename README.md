# npmtest-thenify

#### basic test coverage for  [thenify (v3.2.1)](https://github.com/thenables/thenify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-thenify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-thenify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-thenify.svg)](https://travis-ci.org/npmtest/node-npmtest-thenify)

#### Promisify a callback-based function

[![NPM](https://nodei.co/npm/thenify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/thenify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-thenify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-thenify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-thenify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-thenify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-thenify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-thenify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-thenify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-thenify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-thenify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-thenify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-thenify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-thenify/build/test-report.html](https://npmtest.github.io/node-npmtest-thenify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-thenify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-thenify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-thenify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-thenify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-thenify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-thenify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/thenables/thenify/issues"
    },
    "dependencies": {
        "any-promise": "^1.0.0"
    },
    "description": "Promisify a callback-based function",
    "devDependencies": {
        "bluebird": "^3.1.1",
        "istanbul": "^0.4.0",
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "251fd1c80aff6e5cf57cb179ab1fcb724269bd11",
        "tarball": "https://registry.npmjs.org/thenify/-/thenify-3.2.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "42e93a084347eed9ad34cd3f77728e7fe9b2c1c5",
    "homepage": "https://github.com/thenables/thenify#readme",
    "keywords": [
        "promisify",
        "promise",
        "thenify",
        "then",
        "es6"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jongleberry"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "thenify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thenables/thenify.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "3.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
