# test coverage for  [csurf (v1.9.0)](https://github.com/expressjs/csurf)  [![npm package](https://img.shields.io/npm/v/npmtest-csurf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csurf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csurf.svg)](https://travis-ci.org/npmtest/node-npmtest-csurf)
#### CSRF token middleware

[![NPM](https://nodei.co/npm/csurf.png?downloads=true)](https://www.npmjs.com/package/csurf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csurf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csurf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csurf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csurf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csurf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csurf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csurf/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csurf/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-csurf/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-csurf/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-csurf%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csurf/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csurf/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-csurf%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csurf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csurf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csurf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "email": "me@jongleberry.com",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/expressjs/csurf/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "dependencies": {
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6",
        "csrf": "~3.0.3",
        "http-errors": "~1.5.0"
    },
    "description": "CSRF token middleware",
    "devDependencies": {
        "body-parser": "1.15.1",
        "connect": "3.4.1",
        "cookie-parser": "1.4.3",
        "cookie-session": "~1.1.0",
        "eslint": "2.10.2",
        "eslint-config-standard": "5.3.1",
        "eslint-plugin-promise": "1.3.1",
        "eslint-plugin-standard": "1.3.2",
        "istanbul": "0.4.3",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "49d2c6925ffcec7b7de559597c153fa533364133",
        "tarball": "https://registry.npmjs.org/csurf/-/csurf-1.9.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "6359a0298e1e3e937abb96c21958b2a4419d0301",
    "homepage": "https://github.com/expressjs/csurf",
    "keywords": [
        "csrf",
        "tokens",
        "middleware",
        "express"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "csurf",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/csurf.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "mocha --check-leaks --reporter spec --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec test/"
    },
    "version": "1.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
