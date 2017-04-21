# npmtest-sails-rabbitmq

#### basic test coverage for  [sails-rabbitmq (v0.12.3)](https://github.com/tjwebb/sails-rabbitmq)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-rabbitmq.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-rabbitmq) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-rabbitmq.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-rabbitmq)

#### sails-rabbitmq adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-rabbitmq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-rabbitmq)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-rabbitmq/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-rabbitmq/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-rabbitmq/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-rabbitmq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Webb"
    },
    "bugs": {
        "url": "https://github.com/tjwebb/sails-rabbitmq/issues"
    },
    "dependencies": {
        "babel": "^5.6",
        "gulp": "^3.9",
        "gulp-babel": "^5.1.0",
        "lodash": "^3.9.3",
        "rabbit.js": "^0.4.4",
        "waterline": "^0.10.23"
    },
    "description": "sails-rabbitmq adapter for Sails / Waterline",
    "devDependencies": {
        "captains-log": "^0.11.0",
        "mocha": "^2.2.5",
        "sails-disk": "^0.10.8",
        "sails-memory": "^0.10.4"
    },
    "directories": {},
    "dist": {
        "shasum": "2c4e787047f74827c88b43ecfcdba60e32b16b28",
        "tarball": "https://registry.npmjs.org/sails-rabbitmq/-/sails-rabbitmq-0.12.3.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "eslintConfig": {
        "node": true,
        "es6": true
    },
    "gitHead": "e9626c30317b26e957a5158711a61a7b22463126",
    "homepage": "https://github.com/tjwebb/sails-rabbitmq",
    "keywords": [
        "sails-rabbitmq",
        "rabbit",
        "rabbitmq",
        "amqp",
        "adapter",
        "sails",
        "waterline",
        "sails.js",
        "plugin"
    ],
    "license": "MIT",
    "main": "dist/adapter.js",
    "maintainers": [
        {
            "name": "tjwebb"
        }
    ],
    "name": "sails-rabbitmq",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tjwebb/sails-rabbitmq.git"
    },
    "scripts": {
        "prepublish": "gulp build",
        "test": "mocha --recursive --reporter spec --compilers js:babel/register --timeout 500"
    },
    "version": "0.12.3",
    "waterlineAdapter": {
        "type": "sails-rabbitmq",
        "interfaces": [
            "pubsub"
        ],
        "waterlineVersion": "^0.10"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
