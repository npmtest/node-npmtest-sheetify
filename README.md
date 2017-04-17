# test coverage for  [sheetify (v6.0.1)](https://github.com/stackcss/sheetify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sheetify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sheetify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sheetify.svg)](https://travis-ci.org/npmtest/node-npmtest-sheetify)
#### Modular CSS bundler

[![NPM](https://nodei.co/npm/sheetify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sheetify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sheetify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sheetify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sheetify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sheetify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sheetify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sheetify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sheetify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sheetify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sheetify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sheetify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sheetify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sheetify/build/test-report.html](https://npmtest.github.io/node-npmtest-sheetify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sheetify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sheetify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sheetify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sheetify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sheetify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "index.js": "./browser.js"
    },
    "bugs": {
        "url": "https://github.com/stackcss/sheetify/issues"
    },
    "dependencies": {
        "falafel": "^1.2.0",
        "insert-css": "^2.0.0",
        "map-limit": "0.0.1",
        "postcss": "^5.0.10",
        "postcss-prefix": "^2.0.0",
        "resolve": "^1.1.7",
        "stack-trace": "0.0.9",
        "static-eval": "^1.1.0",
        "style-resolve": "^1.0.0",
        "through2": "^2.0.0",
        "xtend": "^4.0.1"
    },
    "description": "Modular CSS bundler",
    "devDependencies": {
        "browserify": "^13.0.0",
        "codecov.io": "^0.1.6",
        "concat-stream": "^1.5.1",
        "css-extract": "^1.1.2",
        "css-type-base": "^1.0.2",
        "css-wipe": "^4.2.2",
        "dependency-check": "^2.5.1",
        "from2-string": "^1.1.0",
        "istanbul": "^0.4.5",
        "jsdom": "^9.4.2",
        "npm-check-updates": "^2.2.0",
        "rimraf": "^2.5.1",
        "sheetify-cssnext": "^1.0.0",
        "standard": "^8.0.0",
        "tape": "^4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b11851aca2f0a149cbc97c7833bd599988d42da5",
        "tarball": "https://registry.npmjs.org/sheetify/-/sheetify-6.0.1.tgz"
    },
    "gitHead": "2d3e9ee67b3de938a8e6e728d304f3b8d413179c",
    "homepage": "https://github.com/stackcss/sheetify#readme",
    "keywords": [
        "modular",
        "css",
        "bundle",
        "browserify",
        "css-modules"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ahdinosaur"
        },
        {
            "name": "hughsk"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "sheetify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stackcss/sheetify.git"
    },
    "scripts": {
        "deps": "dependency-check . --entry transform.js . && dependency-check . --entry transform.js --extra --no-dev -i insert-css",
        "format": "standard --format",
        "test": "standard && npm run deps && tape test/index.js",
        "test:cov": "standard && npm run deps && NODE_ENV=test istanbul cover test/index.js"
    },
    "version": "6.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
