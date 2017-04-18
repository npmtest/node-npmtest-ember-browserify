# npmtest-ember-browserify

#### test coverage for  [ember-browserify (v1.1.13)](https://github.com/ef4/ember-browserify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-browserify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-browserify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-browserify.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-browserify)

#### ember-cli addon for easily loading CommonJS modules from npm via browserify.

[![NPM](https://nodei.co/npm/ember-browserify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-browserify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-browserify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-browserify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-browserify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-browserify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-browserify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-browserify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-browserify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-browserify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-browserify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-browserify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-browserify/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-browserify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-browserify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-browserify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-browserify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-browserify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-browserify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-browserify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Edward Faulkner"
    },
    "bugs": {
        "url": "https://github.com/ef4/ember-browserify/issues"
    },
    "dependencies": {
        "acorn": "^2.6.4",
        "broccoli-caching-writer": "^3.0.3",
        "broccoli-kitchen-sink-helpers": "^0.3.1",
        "broccoli-merge-trees": "^1.1.2",
        "broccoli-plugin": "^1.2.1",
        "browserify": "^13.0.0",
        "core-object": "^1.1.0",
        "debug": "^2.2.0",
        "derequire": "^2.0.3",
        "ember-cli-version-checker": "^1.1.4",
        "fs-tree": "^1.0.0",
        "fs-tree-diff": "^0.5.0",
        "lodash": "^4.5.1",
        "md5-hex": "^1.3.0",
        "mkdirp": "^0.5.0",
        "promise-map-series": "^0.2.0",
        "quick-temp": "^0.1.2",
        "rimraf": "^2.2.8",
        "rsvp": "^3.0.14",
        "symlink-or-copy": "^1.0.0",
        "through2": "^2.0.0",
        "walk-sync": "^0.2.7"
    },
    "description": "ember-cli addon for easily loading CommonJS modules from npm via browserify.",
    "devDependencies": {
        "broccoli": "^0.16.8",
        "chai": "^1.10.0",
        "copy-dereference": "^1.0.0",
        "mocha": "^2.0.1",
        "mocha-jshint": "0.0.9",
        "sinon": "^1.12.2",
        "sinon-chai": "^2.6.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "df74eea4adf4694e8c364222f9c5fd605000930b",
        "tarball": "https://registry.npmjs.org/ember-browserify/-/ember-browserify-1.1.13.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "d3a941c95a5a012f44012d7f925907d48c8e608e",
    "homepage": "https://github.com/ef4/ember-browserify#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "asakusuma"
        },
        {
            "name": "ef4"
        },
        {
            "name": "stefanpenner"
        }
    ],
    "name": "ember-browserify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ef4/ember-browserify.git"
    },
    "scripts": {
        "test": "mocha --inline-diffs",
        "test:debug": "mocha debug --inline-diffs"
    },
    "version": "1.1.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
