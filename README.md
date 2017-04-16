# test coverage for  [log4js (v1.1.1)](https://github.com/nomiddlename/log4js-node#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-log4js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-log4js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-log4js.svg)](https://travis-ci.org/npmtest/node-npmtest-log4js)
#### Port of Log4js to work with node.

[![NPM](https://nodei.co/npm/log4js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/log4js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-log4js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-log4js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-log4js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-log4js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-log4js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-log4js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-log4js/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-log4js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-log4js/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-log4js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-log4js/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-log4js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-log4js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-log4js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-log4js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gareth Jones"
    },
    "browser": {
        "os": false
    },
    "bugs": {
        "url": "http://github.com/nomiddlename/log4js-node/issues"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "semver": "^5.3.0",
        "streamroller": "^0.4.0"
    },
    "description": "Port of Log4js to work with node.",
    "devDependencies": {
        "jshint": "^2.9.2",
        "sandboxed-module": "0.1.3",
        "tape": "^4.6.2",
        "vows": "0.7.0"
    },
    "directories": {
        "test": "test",
        "lib": "lib"
    },
    "dist": {
        "shasum": "c21d29c7604089e4f255833e7f94b3461de1ff43",
        "tarball": "https://registry.npmjs.org/log4js/-/log4js-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "1fb4f2f8723e6837dc3269970841184684238f74",
    "homepage": "https://github.com/nomiddlename/log4js-node#readme",
    "keywords": [
        "logging",
        "log",
        "log4j",
        "node"
    ],
    "license": "Apache-2.0",
    "main": "./lib/log4js",
    "maintainers": [
        {
            "name": "csausdev"
        }
    ],
    "name": "log4js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nomiddlename/log4js-node.git"
    },
    "scripts": {
        "pretest": "jshint lib/ test/",
        "test": "tape 'test/tape/**/*.js' && vows test/vows/*.js"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
