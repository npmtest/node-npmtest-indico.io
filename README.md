# npmtest-indico.io

#### basic test coverage for  [indico.io (v0.10.5)](https://github.com/IndicoDataSolutions/IndicoIo-node)  [![npm package](https://img.shields.io/npm/v/npmtest-indico.io.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-indico.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-indico.io.svg)](https://travis-ci.org/npmtest/node-npmtest-indico.io)

#### A Node.js wrapper for the Indico’s API

[![NPM](https://nodei.co/npm/indico.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/indico.io)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-indico.io/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-indico.io/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-indico.io/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-indico.io/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-indico.io/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-indico.io/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-indico.io/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-indico.io/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-indico.io/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-indico.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-indico.io/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-indico.io/build/test-report.html](https://npmtest.github.io/node-npmtest-indico.io/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-indico.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-indico.io/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-indico.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-indico.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-indico.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "indico.io",
    "description": "A Node.js wrapper for the Indico’s API",
    "version": "0.10.5",
    "homepage": "https://github.com/IndicoDataSolutions/IndicoIo-node",
    "author": {
        "name": "Joseph Núñez <toctochello@gmail.com>"
    },
    "contributors": [
        "Madison May <madison@indico.io>",
        "Chris Lee <chris@indico.io>",
        "Aidan McLaughlin <aidan@indico.io"
    ],
    "keywords": [],
    "repository": {
        "type": "git",
        "url": "git://github.com/IndicoDataSolutions/IndicoIo-node.git"
    },
    "bugs": {
        "url": "https://github.com/IndicoDataSolutions/IndicoIo-node/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/IndicoDataSolutions/IndicoIo-node/blob/master/LICENSE"
        }
    ],
    "main": "./lib/indico",
    "dependencies": {
        "bluebird": "^2.9.24",
        "config-ini": "^0.2.2",
        "expand-tilde": "^1.2.0",
        "file-type": "^2.11.0",
        "request": "^2.36.0",
        "valid-url": "^1.0.9"
    },
    "optionalDependencies": {
        "lwip": "^0.0.9"
    },
    "devDependencies": {
        "should": "~3.0.1",
        "mocha": "~1.17.0",
        "chai": "1.9.1"
    },
    "scripts": {
        "test": "mocha test/*.js test/integration/*.js"
    },
    "js-flags": "--harmony"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
