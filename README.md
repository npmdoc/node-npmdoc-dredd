# npmdoc-dredd

#### api documentation for  [dredd (v3.4.2)](https://github.com/apiaryio/dredd#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-dredd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dredd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dredd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dredd)

#### HTTP API Testing Framework

[![NPM](https://nodei.co/npm/dredd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dredd)

- [https://npmdoc.github.io/node-npmdoc-dredd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dredd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dredd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Apiary Czech Republic, s.r.o."
    },
    "bin": {
        "dredd": "bin/dredd"
    },
    "bugs": {
        "url": "https://github.com/apiaryio/dredd/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "async": "^2.3.0",
        "caseless": "^0.12.0",
        "chai": "^3.5.0",
        "clone": "^2.1.1",
        "coffee-script": "^1.12.5",
        "colors": "^1.1.2",
        "cross-spawn": "^5.0.1",
        "dredd-transactions": "^4.0.0",
        "file": "^0.2.2",
        "gavel": "^1.1.0",
        "glob": "^7.0.5",
        "html": "^1.0.0",
        "htmlencode": "0.0.4",
        "inquirer": "^1.1.0",
        "js-yaml": "^3.8.3",
        "markdown-it": "^8.3.1",
        "optimist": "^0.6.1",
        "pitboss-ng": "^0.3.2",
        "proxyquire": "^1.7.10",
        "request": "^2.81.0",
        "spawn-args": "^0.2.0",
        "uuid": "^3.0.0",
        "which": "^1.2.14",
        "winston": "^2.2.0"
    },
    "description": "HTTP API Testing Framework",
    "devDependencies": {
        "body-parser": "^1.17.1",
        "coffee-coverage": "^2.0.1",
        "coffeelint": "^1.15.7",
        "conventional-changelog-lint": "^1.1.9",
        "coveralls": "^2.13.0",
        "cz-conventional-changelog": "^2.0.0",
        "drafter": "^1.0.0",
        "ect": "^0.5.9",
        "express": "^4.15.2",
        "jscoverage": "^0.6.0",
        "lcov-result-merger": "^1.2.0",
        "mocha": "^3.0.0",
        "mocha-lcov-reporter": "^1.3.0",
        "nock": "^9.0.13",
        "ps-node": "^0.1.5",
        "semantic-release": "^6.3.2",
        "sinon": "^2.1.0",
        "sync-exec": "^0.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "89f6dc287c5a34bb97d3515f766fb23af4a92446",
        "tarball": "https://registry.npmjs.org/dredd/-/dredd-3.4.2.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "459d9369264ec1b5f02748b7efcc30a4babddf0a",
    "homepage": "https://github.com/apiaryio/dredd#readme",
    "keywords": [
        "api",
        "test",
        "testing",
        "documenation",
        "integration",
        "acceptance"
    ],
    "license": "MIT",
    "main": "lib/dredd.js",
    "maintainers": [
        {
            "name": "abtris"
        },
        {
            "name": "almad"
        },
        {
            "name": "apiary"
        },
        {
            "name": "apiary-sre"
        },
        {
            "name": "honzajavorek"
        },
        {
            "name": "kubakubula"
        },
        {
            "name": "netmilk"
        },
        {
            "name": "pksunkara"
        },
        {
            "name": "tu1ly"
        },
        {
            "name": "vincenzo"
        },
        {
            "name": "zdne"
        }
    ],
    "name": "dredd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/apiaryio/dredd.git"
    },
    "scripts": {
        "build": "coffee -b -c -o lib/ src/ && coffee scripts/generate-cli-docs.coffee",
        "coveralls": "scripts/coveralls.sh",
        "docs:build": "mkdocs build",
        "docs:serve": "mkdocs serve",
        "lint": "conventional-changelog-lint --from=master && coffeelint src",
        "prepublish": "npm run build",
        "pretest": "npm run build",
        "semantic-release": "scripts/semantic-release.sh",
        "test": "mocha \"test/**/*-test.coffee\"",
        "test:coverage": "scripts/coverage.sh",
        "test:hooks-handlers": "coffee scripts/test-hooks-handlers.coffee"
    },
    "version": "3.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
