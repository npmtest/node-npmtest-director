# npmtest-director

#### basic test coverage for  [director (v1.2.8)](https://github.com/flatiron/director)  [![npm package](https://img.shields.io/npm/v/npmtest-director.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-director) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-director.svg)](https://travis-ci.org/npmtest/node-npmtest-director)

#### A client Side/Server Side Router

[![NPM](https://nodei.co/npm/director.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/director)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-director/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-director/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-director/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-director/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-director/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-director/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-director/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-director/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-director/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-director/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-director/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-director/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-director/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-director/build/test-report.html](https://npmtest.github.io/node-npmtest-director/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-director/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-director/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-director/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-director/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-director/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-director/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-director/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-director/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "browserify": "./build/director",
    "bugs": {
        "url": "https://github.com/flatiron/director/issues"
    },
    "dependencies": {},
    "description": "A client Side/Server Side Router",
    "devDependencies": {
        "api-easy": "0.4.x",
        "codesurgeon": "https://github.com/hij1nx/codesurgeon/tarball/master",
        "colors": "1.0.x",
        "qunitjs": "1.9.x",
        "request": "2.49.x",
        "uglify-js": "2.4.x",
        "vows": "0.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c6d9b4dd890e9aff5365183fe9cc8e73994cf2d5",
        "tarball": "https://registry.npmjs.org/director/-/director-1.2.8.tgz"
    },
    "ender": "./build/ender.js",
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "b507baed25cfd38307808ea41a0d6305ee6e1ebf",
    "homepage": "https://github.com/flatiron/director",
    "keywords": [
        "URL",
        "router",
        "http",
        "cli",
        "flatiron",
        "client side",
        "ender"
    ],
    "main": "./lib/director",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "jcrugzz"
        },
        {
            "name": "swaagie"
        }
    ],
    "name": "director",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/flatiron/director.git"
    },
    "scripts": {
        "test": "vows test/server/*/*-test.js --spec"
    },
    "version": "1.2.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
