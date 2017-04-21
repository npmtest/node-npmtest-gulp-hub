# npmtest-gulp-hub

#### basic test coverage for  [gulp-hub (v0.8.0)](https://github.com/frankwallis/gulp-hub)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-hub.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-hub) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-hub.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-hub)

#### A gulp plugin to run tasks from multiple gulpfiles

[![NPM](https://nodei.co/npm/gulp-hub.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-hub)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-hub/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-hub/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-hub/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-hub/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-hub/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-hub/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-hub/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-hub/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-hub/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-hub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-hub/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-hub/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-hub/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-hub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-hub/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-hub/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-hub/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-hub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-hub/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-hub/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-hub/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-hub",
    "description": "A gulp plugin to run tasks from multiple gulpfiles",
    "version": "0.8.0",
    "homepage": "https://github.com/frankwallis/gulp-hub",
    "author": {
        "name": "Frank Wallis"
    },
    "contributors": [
        "Rob McGuire-Dale <rmcguir@rei.com>",
        "Andrew Gatlabayan <agatlab@rei.com>"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/frankwallis/gulp-hub.git"
    },
    "bugs": {
        "url": "https://github.com/frankwallis/gulp-hub/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/frankwallis/gulp-hub/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/index.js",
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "test": "gulp test"
    },
    "dependencies": {
        "callsite": "^1.0.0",
        "glob": "^7.0.3",
        "gulp": "^3.8.10",
        "gulp-util": "^3.0.7",
        "lodash": "^4.13.1",
        "proxyquire": "^1.0.1",
        "run-sequence": "^1.0.2"
    },
    "devDependencies": {
        "gulp": "^3.5.5",
        "gulp-bump": "^2.1.0",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^2.2.0",
        "mocha": "^2.5.3",
        "should": "^9.0.2",
        "sinon": "^1.10.3"
    },
    "keywords": [
        "gulp",
        "hub",
        "grunt-hub",
        "gulp-chug",
        "multi",
        "gulpfriendly"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
