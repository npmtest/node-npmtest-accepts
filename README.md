# npmtest-accepts

#### basic test coverage for  [accepts (v1.3.3)](https://github.com/jshttp/accepts#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-accepts.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-accepts) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-accepts.svg)](https://travis-ci.org/npmtest/node-npmtest-accepts)

#### Higher-level content negotiation

[![NPM](https://nodei.co/npm/accepts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/accepts)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-accepts/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-accepts/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-accepts/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-accepts/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-accepts/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-accepts/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-accepts/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-accepts/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-accepts/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-accepts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-accepts/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-accepts/build/test-report.html](https://npmtest.github.io/node-npmtest-accepts/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-accepts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-accepts/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-accepts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-accepts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-accepts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-accepts/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-accepts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-accepts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/accepts/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "mime-types": "~2.1.11",
        "negotiator": "0.6.1"
    },
    "description": "Higher-level content negotiation",
    "devDependencies": {
        "istanbul": "0.4.3",
        "mocha": "~1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "c3ca7434938648c3e0d9c1e328dd68b622c284ca",
        "tarball": "https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "3e925b1e65ed7da2798849683d49814680dfa426",
    "homepage": "https://github.com/jshttp/accepts#readme",
    "keywords": [
        "content",
        "negotiation",
        "accept",
        "accepts"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "accepts",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/accepts.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --check-leaks --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
