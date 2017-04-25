# npmtest-cookie

#### basic test coverage for  [cookie (v0.3.1)](https://github.com/jshttp/cookie)  [![npm package](https://img.shields.io/npm/v/npmtest-cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cookie.svg)](https://travis-ci.org/npmtest/node-npmtest-cookie)

#### HTTP server cookie parsing and serialization

[![NPM](https://nodei.co/npm/cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cookie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cookie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cookie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cookie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cookie/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cookie/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cookie/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cookie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cookie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cookie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cookie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cookie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cookie/build/test-report.html](https://npmtest.github.io/node-npmtest-cookie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cookie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cookie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roman Shtylman"
    },
    "bugs": {
        "url": "https://github.com/jshttp/cookie/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {},
    "description": "HTTP server cookie parsing and serialization",
    "devDependencies": {
        "istanbul": "0.4.3",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "e7e0a1f9ef43b4c8ba925c5c5a96e806d16873bb",
        "tarball": "https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "e3c77d497d66c8b8d4b677b8954c1b192a09f0b3",
    "homepage": "https://github.com/jshttp/cookie",
    "keywords": [
        "cookie",
        "cookies"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "cookie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/cookie.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "0.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
