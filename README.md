# npmtest-node-cron

#### test coverage for  [node-cron (v1.1.3)](http://merencia.com/node-cron/)  [![npm package](https://img.shields.io/npm/v/npmtest-node-cron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-cron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-cron.svg)](https://travis-ci.org/npmtest/node-npmtest-node-cron)

#### A simple cron-like task scheduler for Node.js

[![NPM](https://nodei.co/npm/node-cron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-cron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-cron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-cron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-cron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-cron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-cron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-cron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-cron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-cron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-cron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-cron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-cron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-cron/build/test-report.html](https://npmtest.github.io/node-npmtest-node-cron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-cron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-cron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-cron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-cron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-cron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-cron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-cron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-cron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lucas Merencia"
    },
    "bugs": {
        "url": "https://github.com/merencia/node-cron/issues"
    },
    "dependencies": {},
    "description": "A simple cron-like task scheduler for Node.js",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "expect.js": "^0.3.1",
        "istanbul": "^0.4.2",
        "mocha": "^3.0.2",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "f161c743812302d50f5251bd93ca57019a5298d2",
        "tarball": "https://registry.npmjs.org/node-cron/-/node-cron-1.1.3.tgz"
    },
    "gitHead": "a042f1209ebf99cf5e3a1783bb33e0e434f84cde",
    "homepage": "http://merencia.com/node-cron/",
    "keywords": [
        "cron",
        "scheduler",
        "schedule",
        "task",
        "job"
    ],
    "license": "ISC",
    "main": "src/node-cron.js",
    "maintainers": [
        {
            "name": "merencia"
        }
    ],
    "name": "node-cron",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/merencia/node-cron.git"
    },
    "scripts": {
        "check": "npm run coverage && npm run coveralls",
        "coverage": "istanbul cover _mocha -- --recursive",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "test": "./node_modules/mocha/bin/mocha --recursive"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
