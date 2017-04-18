# npmtest-ponte

#### test coverage for  [ponte (v0.0.16)](https://github.com/eclipse/ponte#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ponte.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ponte) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ponte.svg)](https://travis-ci.org/npmtest/node-npmtest-ponte)

#### The Internet of Things Bridge for REST developers

[![NPM](https://nodei.co/npm/ponte.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ponte)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ponte/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ponte/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ponte/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ponte/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ponte/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ponte/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ponte/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ponte/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ponte/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ponte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ponte/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ponte/build/test-report.html](https://npmtest.github.io/node-npmtest-ponte/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ponte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ponte/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ponte/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ponte/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ponte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ponte/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ponte/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ponte/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bin": {
        "ponte": "./bin/ponte"
    },
    "bugs": {
        "url": "https://bugs.eclipse.org/bugs/buglist.cgi?component=Core&product=Ponte&resolution=---"
    },
    "dependencies": {
        "ascoltatori": "~2.0.1",
        "async": "~1.5.0",
        "bunyan": "~1.5.1",
        "callback-stream": "~1.1.0",
        "coap": "~0.13.0",
        "commander": "~2.9.0",
        "corsify": "~2.1.0",
        "mosca": "~1.1.2",
        "st": "~1.1.0",
        "xtend": "~4.0.1"
    },
    "description": "The Internet of Things Bridge for REST developers",
    "devDependencies": {
        "chai": "~3.4.1",
        "jshint": "~2.9.1",
        "mocha": "~2.3.4",
        "mqtt": "~1.7.0",
        "pre-commit": "~1.1.2",
        "sinon": "~1.17.2",
        "superagent": "~1.7.1",
        "supertest": "~1.1.0",
        "tmp": "0.0.28"
    },
    "directories": {},
    "dist": {
        "shasum": "3ba232f309fe72f660859060d7b53c9b1bf4c15d",
        "tarball": "https://registry.npmjs.org/ponte/-/ponte-0.0.16.tgz"
    },
    "gitHead": "a2e87433b7bb87970cf8dcc2d6bccba2f4290e3f",
    "homepage": "https://github.com/eclipse/ponte#readme",
    "license": "EPL-1.0 OR BSD-3-Clause",
    "main": "lib/ponte.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "ponte",
    "optionalDependencies": {},
    "pre-commit": [
        "jshint-lib",
        "jshint-test",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eclipse/ponte.git"
    },
    "scripts": {
        "ci": "mocha --recursive --bail --watch test",
        "jshint-lib": "jshint lib",
        "jshint-test": "jshint test",
        "start": "./bin/ponte -v | bunyan",
        "test": "mocha --recursive --bail --reporter spec test"
    },
    "version": "0.0.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
