# npmtest-http-errors

#### basic test coverage for  [http-errors (v1.6.1)](https://github.com/jshttp/http-errors#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-http-errors.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-http-errors) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-http-errors.svg)](https://travis-ci.org/npmtest/node-npmtest-http-errors)

#### Create HTTP error objects

[![NPM](https://nodei.co/npm/http-errors.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http-errors)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-http-errors/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-errors/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-http-errors/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-http-errors/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-http-errors/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-http-errors/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-http-errors/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-http-errors/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-http-errors/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-errors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-http-errors/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-http-errors/build/test-report.html](https://npmtest.github.io/node-npmtest-http-errors/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-http-errors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-http-errors/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-http-errors/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http-errors/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-errors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-errors/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-http-errors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-http-errors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/jshttp/http-errors/issues"
    },
    "contributors": [
        {
            "name": "Alan Plum"
        },
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {
        "depd": "1.1.0",
        "inherits": "2.0.3",
        "setprototypeof": "1.0.3",
        "statuses": ">= 1.3.1 < 2"
    },
    "description": "Create HTTP error objects",
    "devDependencies": {
        "eslint": "3.16.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5f8b8ed98aca545656bf572997387f904a722257",
        "tarball": "https://registry.npmjs.org/http-errors/-/http-errors-1.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "index.js",
        "HISTORY.md",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "d8d95dbc84c913a594b7fca07096697412af7edd",
    "homepage": "https://github.com/jshttp/http-errors#readme",
    "keywords": [
        "http",
        "error"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "egeste"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "http-errors",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/http-errors.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
