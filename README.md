# npmtest-winston-daily-rotate-file

#### basic test coverage for  [winston-daily-rotate-file (v1.4.6)](https://github.com/winstonjs/winston-daily-rotate-file#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-winston-daily-rotate-file.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-winston-daily-rotate-file) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-winston-daily-rotate-file.svg)](https://travis-ci.org/npmtest/node-npmtest-winston-daily-rotate-file)

#### A transport for winston which logs to a rotating file each day.

[![NPM](https://nodei.co/npm/winston-daily-rotate-file.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winston-daily-rotate-file)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-winston-daily-rotate-file/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-winston-daily-rotate-file/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/test-report.html](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-winston-daily-rotate-file/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winston-daily-rotate-file/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-daily-rotate-file/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-daily-rotate-file/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-winston-daily-rotate-file/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/winstonjs/winston-daily-rotate-file/issues"
    },
    "dependencies": {},
    "description": "A transport for winston which logs to a rotating file each day.",
    "devDependencies": {
        "chai": "3.5.0",
        "eslint": "2.10.2",
        "eslint-config-xo-space": "0.13.0",
        "mkdirp": "0.5.1",
        "mocha": "2.4.5",
        "moment": "2.13.0",
        "rimraf": "2.5.2",
        "timekeeper": "^0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f204b6ada19a5386fdf52fe997d8e10e43ff7788",
        "tarball": "https://registry.npmjs.org/winston-daily-rotate-file/-/winston-daily-rotate-file-1.4.6.tgz"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "node": true,
            "mocha": true
        }
    },
    "gitHead": "6cb4c688c09d4c1ddf5e664825fc108c77e110b6",
    "homepage": "https://github.com/winstonjs/winston-daily-rotate-file#readme",
    "keywords": [
        "winston",
        "daily-rotate-file",
        "log-rotate",
        "logrotate"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "mattberther"
        }
    ],
    "name": "winston-daily-rotate-file",
    "optionalDependencies": {},
    "peerDependencies": {
        "winston": "2.x"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/winstonjs/winston-daily-rotate-file.git"
    },
    "scripts": {
        "postversion": "git push && git push --tags && npm publish",
        "preversion": "npm test",
        "test": "mocha && eslint ."
    },
    "version": "1.4.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
