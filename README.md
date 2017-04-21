# npmtest-pubsub-js

#### basic test coverage for  [pubsub-js (v1.5.6)](https://github.com/mroderick/PubSubJS#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pubsub-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pubsub-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pubsub-js.svg)](https://travis-ci.org/npmtest/node-npmtest-pubsub-js)

#### Dependency free publish/subscribe library

[![NPM](https://nodei.co/npm/pubsub-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pubsub-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pubsub-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pubsub-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pubsub-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pubsub-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pubsub-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pubsub-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pubsub-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pubsub-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pubsub-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pubsub-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pubsub-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pubsub-js/build/test-report.html](https://npmtest.github.io/node-npmtest-pubsub-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pubsub-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pubsub-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pubsub-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pubsub-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Morgan Roderick",
        "url": "http://roderick.dk"
    },
    "bugs": {
        "url": "https://github.com/mroderick/PubSubJS/issues"
    },
    "dependencies": {},
    "description": "Dependency free publish/subscribe library",
    "devDependencies": {
        "buster": "0.7.18",
        "grunt": "0.4.5",
        "grunt-buster": "0.3.2",
        "grunt-cli": "0.1.13",
        "grunt-contrib-concat": "0.5.0",
        "jslint": "0.7.2",
        "phantomjs": "1.9.13"
    },
    "directories": {
        "lib": "src",
        "test": "test"
    },
    "dist": {
        "shasum": "8bf6adbb810ffb7ec5129d178084bd7d7bb97de2",
        "tarball": "https://registry.npmjs.org/pubsub-js/-/pubsub-js-1.5.6.tgz"
    },
    "gitHead": "38800db48fe5b855c2c7d75903d07740ce5c63d6",
    "homepage": "https://github.com/mroderick/PubSubJS#readme",
    "keywords": [
        "pub/sub",
        "pubsub",
        "publish/subscribe",
        "publish",
        "subscribe"
    ],
    "license": "MIT",
    "main": "./src/pubsub.js",
    "maintainers": [
        {
            "name": "mrgnrdrck"
        }
    ],
    "name": "pubsub-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mroderick/PubSubJS.git"
    },
    "scripts": {
        "lint": "$(npm bin)/jslint src/**/*.js test/**/*.js",
        "test": "npm run lint && $(npm bin)/grunt test"
    },
    "version": "1.5.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
