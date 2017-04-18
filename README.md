# npmtest-hapi

#### test coverage for  [hapi (v16.1.1)](http://hapijs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-hapi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hapi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hapi.svg)](https://travis-ci.org/npmtest/node-npmtest-hapi)

#### HTTP Server framework

[![NPM](https://nodei.co/npm/hapi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hapi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hapi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hapi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hapi/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hapi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hapi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hapi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hapi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hapi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hapi/build/test-report.html](https://npmtest.github.io/node-npmtest-hapi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hapi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hapi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hapi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hapi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hapi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hapi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hapi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hapi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/hapi/issues"
    },
    "dependencies": {
        "accept": "2.x.x",
        "ammo": "2.x.x",
        "boom": "4.x.x",
        "call": "4.x.x",
        "catbox": "7.x.x",
        "catbox-memory": "2.x.x",
        "cryptiles": "3.x.x",
        "heavy": "4.x.x",
        "hoek": "4.x.x",
        "iron": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x",
        "mimos": "3.x.x",
        "podium": "^1.2.x",
        "shot": "3.x.x",
        "statehood": "5.x.x",
        "subtext": "^4.3.x",
        "topo": "2.x.x"
    },
    "description": "HTTP Server framework",
    "devDependencies": {
        "code": "4.x.x",
        "handlebars": "4.x.x",
        "inert": "4.x.x",
        "lab": "11.x.x",
        "vision": "4.x.x",
        "wreck": "10.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "0466db0703ba15cd00f07175ccf394d9cb56b1e0",
        "tarball": "https://registry.npmjs.org/hapi/-/hapi-16.1.1.tgz"
    },
    "engines": {
        "node": ">=4.5.0"
    },
    "gitHead": "770cc7bad15122f796d938738b7c05b66d2f4b7f",
    "homepage": "http://hapijs.com",
    "keywords": [
        "framework",
        "http",
        "api",
        "web"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        }
    ],
    "name": "hapi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/hapi.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L -m 3000",
        "test-cov-html": "lab -a code -r html -o coverage.html -m 3000",
        "test-tap": "lab -a code -r tap -o tests.tap -m 3000"
    },
    "version": "16.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
