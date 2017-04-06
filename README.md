# api documentation for  [dredd (v3.4.1)](https://github.com/apiaryio/dredd#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-dredd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dredd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dredd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dredd)
#### HTTP API Testing Framework

[![NPM](https://nodei.co/npm/dredd.png?downloads=true)](https://www.npmjs.com/package/dredd)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-dredd_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dredd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dredd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Apiary Czech Republic, s.r.o.",
        "email": "support@apiary.io"
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
        "async": "^2.0.0-rc.6",
        "caseless": "^0.12.0",
        "chai": "^3.5.0",
        "clone": "^2.0.0",
        "coffee-script": "^1.10.0",
        "colors": "^1.1.2",
        "cross-spawn": "^5.0.1",
        "dredd-transactions": "^4.0.0",
        "file": "^0.2.2",
        "gavel": "^1.0.0",
        "glob": "^7.0.5",
        "html": "^1.0.0",
        "htmlencode": "0.0.4",
        "inquirer": "^1.1.0",
        "js-yaml": "^3.6.1",
        "markdown-it": "^8.0.1",
        "optimist": "^0.6.1",
        "pitboss-ng": "^0.3.2",
        "proxyquire": "^1.7.10",
        "request": "^2.79.0",
        "spawn-args": "^0.2.0",
        "sync-exec": "^0.6.2",
        "uuid": "^3.0.0",
        "which": "^1.2.12",
        "winston": "^2.2.0"
    },
    "description": "HTTP API Testing Framework",
    "devDependencies": {
        "body-parser": "^1.15.2",
        "coffee-coverage": "^1.0.1",
        "coffeelint": "^1.15.7",
        "conventional-changelog-lint": "^1.1.0",
        "coveralls": "^2.11.9",
        "cz-conventional-changelog": "^1.1.6",
        "drafter": "^1.0.0",
        "ect": "^0.5.9",
        "express": "^4.14.0",
        "jscoverage": "^0.6.0",
        "lcov-result-merger": "^1.2.0",
        "mocha": "^3.0.0",
        "mocha-lcov-reporter": "^1.3.0",
        "nock": "^9.0.4",
        "ps-node": "^0.1.4",
        "semantic-release": "^6.3.2",
        "sinon": "^1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "74050045799cda87dbae6e34cfa8f191c242edd1",
        "tarball": "https://registry.npmjs.org/dredd/-/dredd-3.4.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "b55fa667ff2904f457e193509fde84c5690376df",
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
            "name": "abtris",
            "email": "ladislav@apiary.io"
        },
        {
            "name": "almad",
            "email": "bugs@almad.net"
        },
        {
            "name": "apiary",
            "email": "lukas+npm@apiary.io"
        },
        {
            "name": "apiary-sre",
            "email": "sre@apiary.io"
        },
        {
            "name": "honzajavorek",
            "email": "mail@honzajavorek.cz"
        },
        {
            "name": "kubakubula",
            "email": "kubula@apiary.io"
        },
        {
            "name": "netmilk",
            "email": "adam@apiary.io"
        },
        {
            "name": "pksunkara",
            "email": "pavan.sss1991@gmail.com"
        },
        {
            "name": "tu1ly",
            "email": "tully@apiary.io"
        },
        {
            "name": "vincenzo",
            "email": "vincenzo@apiary.io"
        },
        {
            "name": "zdne",
            "email": "z@apiary.io"
        }
    ],
    "name": "dredd",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "3.4.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module dredd](#apidoc.module.dredd)
1.  [function <span class="apidocSignatureSpan">dredd.</span>dredd_command (options, cb)](#apidoc.element.dredd.dredd_command)
1.  [function <span class="apidocSignatureSpan">dredd.</span>hooks (options)](#apidoc.element.dredd.hooks)
1.  [function <span class="apidocSignatureSpan">dredd.</span>hooks_worker_client (runner)](#apidoc.element.dredd.hooks_worker_client)
1.  [function <span class="apidocSignatureSpan">dredd.</span>transaction_runner (configuration1)](#apidoc.element.dredd.transaction_runner)
1.  object <span class="apidocSignatureSpan">dredd.</span>blueprint_utils
1.  object <span class="apidocSignatureSpan">dredd.</span>child_process
1.  object <span class="apidocSignatureSpan">dredd.</span>config_utils
1.  object <span class="apidocSignatureSpan">dredd.</span>configuration
1.  object <span class="apidocSignatureSpan">dredd.</span>dredd_command.prototype
1.  object <span class="apidocSignatureSpan">dredd.</span>hooks.prototype
1.  object <span class="apidocSignatureSpan">dredd.</span>hooks_worker_client.prototype
1.  object <span class="apidocSignatureSpan">dredd.</span>interactive_config
1.  object <span class="apidocSignatureSpan">dredd.</span>logger
1.  object <span class="apidocSignatureSpan">dredd.</span>options
1.  object <span class="apidocSignatureSpan">dredd.</span>transaction_runner.prototype
1.  object <span class="apidocSignatureSpan">dredd.</span>which

#### [module dredd.blueprint_utils](#apidoc.module.dredd.blueprint_utils)
1.  [function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>characterIndexToPosition (charIndex, code)](#apidoc.element.dredd.blueprint_utils.characterIndexToPosition)
1.  [function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>rangesToLinesText (ranges)](#apidoc.element.dredd.blueprint_utils.rangesToLinesText)
1.  [function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>sortNumbersAscending (a, b)](#apidoc.element.dredd.blueprint_utils.sortNumbersAscending)
1.  [function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>warningLocationToRanges (warningLocation, text)](#apidoc.element.dredd.blueprint_utils.warningLocationToRanges)

#### [module dredd.child_process](#apidoc.module.dredd.child_process)
1.  [function <span class="apidocSignatureSpan">dredd.child_process.</span>signalKill (childProcess, callback)](#apidoc.element.dredd.child_process.signalKill)
1.  [function <span class="apidocSignatureSpan">dredd.child_process.</span>signalTerm (childProcess, callback)](#apidoc.element.dredd.child_process.signalTerm)
1.  [function <span class="apidocSignatureSpan">dredd.child_process.</span>spawn ()](#apidoc.element.dredd.child_process.spawn)
1.  [function <span class="apidocSignatureSpan">dredd.child_process.</span>terminate (childProcess, options, callback)](#apidoc.element.dredd.child_process.terminate)

#### [module dredd.config_utils](#apidoc.module.dredd.config_utils)
1.  [function <span class="apidocSignatureSpan">dredd.config_utils.</span>load (path)](#apidoc.element.dredd.config_utils.load)
1.  [function <span class="apidocSignatureSpan">dredd.config_utils.</span>parseCustom (customArray)](#apidoc.element.dredd.config_utils.parseCustom)
1.  [function <span class="apidocSignatureSpan">dredd.config_utils.</span>save (argsOrigin, path)](#apidoc.element.dredd.config_utils.save)

#### [module dredd.configuration](#apidoc.module.dredd.configuration)
1.  [function <span class="apidocSignatureSpan">dredd.configuration.</span>applyConfiguration (config)](#apidoc.element.dredd.configuration.applyConfiguration)
1.  [function <span class="apidocSignatureSpan">dredd.configuration.</span>applyLoggingOptions (options)](#apidoc.element.dredd.configuration.applyLoggingOptions)

#### [module dredd.dredd_command](#apidoc.module.dredd.dredd_command)
1.  [function <span class="apidocSignatureSpan">dredd.</span>dredd_command (options, cb)](#apidoc.element.dredd.dredd_command.dredd_command)

#### [module dredd.dredd_command.prototype](#apidoc.module.dredd.dredd_command.prototype)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>checkRequiredArgs ()](#apidoc.element.dredd.dredd_command.prototype.checkRequiredArgs)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>commandSigInt ()](#apidoc.element.dredd.dredd_command.prototype.commandSigInt)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>exitWithStatus (error, stats)](#apidoc.element.dredd.dredd_command.prototype.exitWithStatus)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>initConfig ()](#apidoc.element.dredd.dredd_command.prototype.initConfig)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>initDredd (configuration)](#apidoc.element.dredd.dredd_command.prototype.initDredd)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>lastArgvIsApiEndpoint ()](#apidoc.element.dredd.dredd_command.prototype.lastArgvIsApiEndpoint)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>loadDreddFile ()](#apidoc.element.dredd.dredd_command.prototype.loadDreddFile)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>logDebuggingInfo (config)](#apidoc.element.dredd.dredd_command.prototype.logDebuggingInfo)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>moveBlueprintArgToPath ()](#apidoc.element.dredd.dredd_command.prototype.moveBlueprintArgToPath)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>parseCustomConfig ()](#apidoc.element.dredd.dredd_command.prototype.parseCustomConfig)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>run ()](#apidoc.element.dredd.dredd_command.prototype.run)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runDredd (dreddInstance)](#apidoc.element.dredd.dredd_command.prototype.runDredd)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runExitingActions ()](#apidoc.element.dredd.dredd_command.prototype.runExitingActions)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runServerAndThenDredd (callback)](#apidoc.element.dredd.dredd_command.prototype.runServerAndThenDredd)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>setExitOrCallback ()](#apidoc.element.dredd.dredd_command.prototype.setExitOrCallback)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>setOptimistArgv ()](#apidoc.element.dredd.dredd_command.prototype.setOptimistArgv)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>stopServer (callback)](#apidoc.element.dredd.dredd_command.prototype.stopServer)
1.  [function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>takeRestOfParamsAsPath ()](#apidoc.element.dredd.dredd_command.prototype.takeRestOfParamsAsPath)

#### [module dredd.hooks](#apidoc.module.dredd.hooks)
1.  [function <span class="apidocSignatureSpan">dredd.</span>hooks (options)](#apidoc.element.dredd.hooks.hooks)

#### [module dredd.hooks.prototype](#apidoc.module.dredd.hooks.prototype)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>addHook (hooks, name, hook)](#apidoc.element.dredd.hooks.prototype.addHook)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>after (name, hook)](#apidoc.element.dredd.hooks.prototype.after)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>afterAll (hook)](#apidoc.element.dredd.hooks.prototype.afterAll)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>afterEach (hook)](#apidoc.element.dredd.hooks.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>before (name, hook)](#apidoc.element.dredd.hooks.prototype.before)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeAll (hook)](#apidoc.element.dredd.hooks.prototype.beforeAll)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeEach (hook)](#apidoc.element.dredd.hooks.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeEachValidation (hook)](#apidoc.element.dredd.hooks.prototype.beforeEachValidation)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeValidation (name, hook)](#apidoc.element.dredd.hooks.prototype.beforeValidation)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>dumpHooksFunctionsToStrings ()](#apidoc.element.dredd.hooks.prototype.dumpHooksFunctionsToStrings)
1.  [function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>log ()](#apidoc.element.dredd.hooks.prototype.log)

#### [module dredd.hooks_worker_client](#apidoc.module.dredd.hooks_worker_client)
1.  [function <span class="apidocSignatureSpan">dredd.</span>hooks_worker_client (runner)](#apidoc.element.dredd.hooks_worker_client.hooks_worker_client)

#### [module dredd.hooks_worker_client.prototype](#apidoc.module.dredd.hooks_worker_client.prototype)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>connectToHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.connectToHandler)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>disconnectFromHandler ()](#apidoc.element.dredd.hooks_worker_client.prototype.disconnectFromHandler)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>registerHooks (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.registerHooks)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>setCommandAndCheckForExecutables (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.setCommandAndCheckForExecutables)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>spawnHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.spawnHandler)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>start (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.start)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>stop (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.stop)
1.  [function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>terminateHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.terminateHandler)

#### [module dredd.interactive_config](#apidoc.module.dredd.interactive_config)
1.  [function <span class="apidocSignatureSpan">dredd.interactive_config.</span>processAnswers (config, answers, callback)](#apidoc.element.dredd.interactive_config.processAnswers)
1.  [function <span class="apidocSignatureSpan">dredd.interactive_config.</span>prompt (config, callback)](#apidoc.element.dredd.interactive_config.prompt)
1.  [function <span class="apidocSignatureSpan">dredd.interactive_config.</span>run (config, callback)](#apidoc.element.dredd.interactive_config.run)
1.  [function <span class="apidocSignatureSpan">dredd.interactive_config.</span>updateCircle ()](#apidoc.element.dredd.interactive_config.updateCircle)
1.  [function <span class="apidocSignatureSpan">dredd.interactive_config.</span>updateTravis ()](#apidoc.element.dredd.interactive_config.updateTravis)

#### [module dredd.logger](#apidoc.module.dredd.logger)
1.  boolean <span class="apidocSignatureSpan">dredd.logger.</span>emitErrs
1.  boolean <span class="apidocSignatureSpan">dredd.logger.</span>exitOnError
1.  boolean <span class="apidocSignatureSpan">dredd.logger.</span>padLevels
1.  boolean <span class="apidocSignatureSpan">dredd.logger.</span>stripColors
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>actual (msg)](#apidoc.element.dredd.logger.actual)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>complete (msg)](#apidoc.element.dredd.logger.complete)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>debug (msg)](#apidoc.element.dredd.logger.debug)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>error (msg)](#apidoc.element.dredd.logger.error)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>expected (msg)](#apidoc.element.dredd.logger.expected)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>fail (msg)](#apidoc.element.dredd.logger.fail)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>hook (msg)](#apidoc.element.dredd.logger.hook)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>info (msg)](#apidoc.element.dredd.logger.info)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>pass (msg)](#apidoc.element.dredd.logger.pass)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>request (msg)](#apidoc.element.dredd.logger.request)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>silly (msg)](#apidoc.element.dredd.logger.silly)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>skip (msg)](#apidoc.element.dredd.logger.skip)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>test (msg)](#apidoc.element.dredd.logger.test)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>verbose (msg)](#apidoc.element.dredd.logger.verbose)
1.  [function <span class="apidocSignatureSpan">dredd.logger.</span>warn (msg)](#apidoc.element.dredd.logger.warn)
1.  number <span class="apidocSignatureSpan">dredd.logger.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>_events
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>_names
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>domain
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>exceptionHandlers
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>filters
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>id
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>levels
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>profilers
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>rewriters
1.  object <span class="apidocSignatureSpan">dredd.logger.</span>transports
1.  string <span class="apidocSignatureSpan">dredd.logger.</span>level

#### [module dredd.transaction_runner](#apidoc.module.dredd.transaction_runner)
1.  [function <span class="apidocSignatureSpan">dredd.</span>transaction_runner (configuration1)](#apidoc.element.dredd.transaction_runner.transaction_runner)

#### [module dredd.transaction_runner.prototype](#apidoc.module.dredd.transaction_runner.prototype)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>config (config)](#apidoc.element.dredd.transaction_runner.prototype.config)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>configureTransaction (transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.configureTransaction)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>createTest (transaction)](#apidoc.element.dredd.transaction_runner.prototype.createTest)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitError (error, test)](#apidoc.element.dredd.transaction_runner.prototype.emitError)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitHookError (error, data)](#apidoc.element.dredd.transaction_runner.prototype.emitHookError)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitResult (transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.emitResult)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>ensureTransactionResultsGeneralSection (transaction)](#apidoc.element.dredd.transaction_runner.prototype.ensureTransactionResultsGeneralSection)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>executeAllTransactions (transactions, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.executeAllTransactions)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>executeTransaction (transaction, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.executeTransaction)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>failTransaction (transaction, reason)](#apidoc.element.dredd.transaction_runner.prototype.failTransaction)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>getFullPath (serverPath, requestPath)](#apidoc.element.dredd.transaction_runner.prototype.getFullPath)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>getRequestOptionsFromTransaction (transaction)](#apidoc.element.dredd.transaction_runner.prototype.getRequestOptionsFromTransaction)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>isMultipart (requestOptions)](#apidoc.element.dredd.transaction_runner.prototype.isMultipart)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>parseServerUrl (serverUrl)](#apidoc.element.dredd.transaction_runner.prototype.parseServerUrl)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>performRequest (options, callback)](#apidoc.element.dredd.transaction_runner.prototype.performRequest)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>performRequestAndValidate (test, transaction, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.performRequestAndValidate)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>replaceLineFeedInBody (transaction, requestOptions)](#apidoc.element.dredd.transaction_runner.prototype.replaceLineFeedInBody)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>run (transactions, callback)](#apidoc.element.dredd.transaction_runner.prototype.run)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runHook (hook, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runHook)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runHooksForData (hooks, data, legacy, callback)](#apidoc.element.dredd.transaction_runner.prototype.runHooksForData)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runLegacyHook (hook, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runLegacyHook)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runSandboxedHookFromString (hookString, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runSandboxedHookFromString)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>sandboxedHookResultsHandler (err, data, results, callback)](#apidoc.element.dredd.transaction_runner.prototype.sandboxedHookResultsHandler)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>sandboxedWrappedCode (hookCode)](#apidoc.element.dredd.transaction_runner.prototype.sandboxedWrappedCode)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>setContentLength (transaction)](#apidoc.element.dredd.transaction_runner.prototype.setContentLength)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>skipTransaction (transaction, reason)](#apidoc.element.dredd.transaction_runner.prototype.skipTransaction)
1.  [function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>validateTransaction (test, transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.validateTransaction)

#### [module dredd.which](#apidoc.module.dredd.which)
1.  [function <span class="apidocSignatureSpan">dredd.</span>which (command)](#apidoc.element.dredd.which.which)



# <a name="apidoc.module.dredd"></a>[module dredd](#apidoc.module.dredd)

#### <a name="apidoc.element.dredd.dredd_command"></a>[function <span class="apidocSignatureSpan">dredd.</span>dredd_command (options, cb)](#apidoc.element.dredd.dredd_command)
- description and source-code
```javascript
function DreddCommand(options, cb) {
  if (options == null) {
    options = {};
  }
  this.cb = cb;
  this.finished = false;
  this.exit = options.exit, this.custom = options.custom;
  this.setExitOrCallback();
  if (this.custom == null) {
    this.custom = {};
  }
  if (!this.custom.cwd || typeof this.custom.cwd !== 'string') {
    this.custom.cwd = process.cwd();
  }
  if (!this.custom.argv || !Array.isArray(this.custom.argv)) {
    this.custom.argv = [];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks"></a>[function <span class="apidocSignatureSpan">dredd.</span>hooks (options)](#apidoc.element.dredd.hooks)
- description and source-code
```javascript
function Hooks(options) {
  if (options == null) {
    options = {};
  }
  this.dumpHooksFunctionsToStrings = bind(this.dumpHooksFunctionsToStrings, this);
  this.log = bind(this.log, this);
  this.afterEach = bind(this.afterEach, this);
  this.beforeEachValidation = bind(this.beforeEachValidation, this);
  this.beforeEach = bind(this.beforeEach, this);
  this.afterAll = bind(this.afterAll, this);
  this.beforeAll = bind(this.beforeAll, this);
  this.after = bind(this.after, this);
  this.beforeValidation = bind(this.beforeValidation, this);
  this.before = bind(this.before, this);
  this.logs = options.logs, this.logger = options.logger;
  this.transactions = {};
  this.beforeHooks = {};
  this.beforeValidationHooks = {};
  this.afterHooks = {};
  this.beforeAllHooks = [];
  this.afterAllHooks = [];
  this.beforeEachHooks = [];
  this.beforeEachValidationHooks = [];
  this.afterEachHooks = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks_worker_client"></a>[function <span class="apidocSignatureSpan">dredd.</span>hooks_worker_client (runner)](#apidoc.element.dredd.hooks_worker_client)
- description and source-code
```javascript
function HooksWorkerClient(runner) {
  var options;
  this.runner = runner;
  options = this.runner.hooks.configuration.options;
  this.language = options.language;
  this.timeout = options['hooks-worker-timeout'] || 5000;
  this.connectTimeout = options['hooks-worker-connect-timeout'] || 1500;
  this.connectRetry = options['hooks-worker-connect-retry'] || 500;
  this.afterConnectWait = options['hooks-worker-after-connect-wait'] || 100;
  this.termTimeout = options['hooks-worker-term-timeout'] || 5000;
  this.termRetry = options['hooks-worker-term-retry'] || 500;
  this.handlerHost = options['hooks-worker-handler-host'] || '127.0.0.1';
  this.handlerPort = options['hooks-worker-handler-port'] || 61321;
  this.handlerMessageDelimiter = '\n';
  this.clientConnected = false;
  this.connectError = false;
  this.emitter = new EventEmitter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.transaction_runner"></a>[function <span class="apidocSignatureSpan">dredd.</span>transaction_runner (configuration1)](#apidoc.element.dredd.transaction_runner)
- description and source-code
```javascript
function TransactionRunner(configuration1) {
  this.configuration = configuration1;
  this.executeTransaction = bind(this.executeTransaction, this);
  this.configureTransaction = bind(this.configureTransaction, this);
  this.logs = [];
  this.hookStash = {};
  this.error = null;
  this.hookHandlerError = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.blueprint_utils"></a>[module dredd.blueprint_utils](#apidoc.module.dredd.blueprint_utils)

#### <a name="apidoc.element.dredd.blueprint_utils.characterIndexToPosition"></a>[function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>characterIndexToPosition (charIndex, code)](#apidoc.element.dredd.blueprint_utils.characterIndexToPosition)
- description and source-code
```javascript
characterIndexToPosition = function (charIndex, code) {
  var codeFragment, ref, row;
  if (charIndex == null) {
    charIndex = 0;
  }
  if (code == null) {
    code = '';
  }
  codeFragment = code.substring(0, charIndex);
  row = (((ref = codeFragment.match(NEWLINE_RE)) != null ? ref.length : void 0) || 0) + 1;
  return {
    row: row
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.blueprint_utils.rangesToLinesText"></a>[function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>rangesToLinesText (ranges)](#apidoc.element.dredd.blueprint_utils.rangesToLinesText)
- description and source-code
```javascript
rangesToLinesText = function (ranges) {
  var i, len, pos, range, rangeIndex, ref;
  pos = '';
  ref = ranges || [];
  for (rangeIndex = i = 0, len = ref.length; i < len; rangeIndex = ++i) {
    range = ref[rangeIndex];
    if (rangeIndex > 0) {
      pos += ', ';
    }
    if (range.start !== range.end) {
      pos += "lines " + range.start + "-" + range.end;
    } else {
      pos += "line " + range.start;
    }
  }
  return pos;
}
```
- example usage
```shell
...
    error = true;
    log = logger.error;
  }
  if (annotation.component === 'apiDescriptionParser') {
    ranges = blueprintUtils.warningLocationToRanges(annotation.location, apiDescriptionDocument);
    message = "Parser " + annotation.type + " in file '" + filename + "': (" + annotation.type + " code " + annotation.code + ") " +
annotation.message + " ";
    if (ranges != null ? ranges.length : void 0) {
      message += "on " + (blueprintUtils.rangesToLinesText(ranges));
    }
    log(message);
  } else {
    transactionName = [annotation.origin.resourceGroupName, annotation.origin.resourceName, annotation.origin.actionName].join(' > ');
    log("Compilation " + annotation.type + " in file '" + filename + "': " + annotation.message + " (" + transactionName + ") ");
  }
}
...
```

#### <a name="apidoc.element.dredd.blueprint_utils.sortNumbersAscending"></a>[function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>sortNumbersAscending (a, b)](#apidoc.element.dredd.blueprint_utils.sortNumbersAscending)
- description and source-code
```javascript
sortNumbersAscending = function (a, b) {
  return a - b;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.blueprint_utils.warningLocationToRanges"></a>[function <span class="apidocSignatureSpan">dredd.blueprint_utils.</span>warningLocationToRanges (warningLocation, text)](#apidoc.element.dredd.blueprint_utils.warningLocationToRanges)
- description and source-code
```javascript
warningLocationToRanges = function (warningLocation, text) {
  var i, j, lastLocation, len, len1, loc, locKey, position, range, ranges, rowIndex, rowsIndexes;
  if (warningLocation == null) {
    warningLocation = [];
  }
  if (text == null) {
    text = '';
  }
  if (!warningLocation.length) {
    return [];
  }
  rowsIndexes = [];
  position = characterIndexToPosition(warningLocation[0][0], text);
  rowsIndexes.push(position.row);
  lastLocation = warningLocation[warningLocation.length - 1];
  if (warningLocation.length > 0) {
    for (locKey = i = 0, len = warningLocation.length; i < len; locKey = ++i) {
      loc = warningLocation[locKey];
      if (!(locKey > 0)) {
        continue;
      }
      position = characterIndexToPosition(loc[0], text);
      rowsIndexes.push(position.row);
    }
  }
  rowsIndexes.sort(sortNumbersAscending);
  ranges = [];
  range = {
    start: rowsIndexes[0],
    end: rowsIndexes[0]
  };
  for (j = 0, len1 = rowsIndexes.length; j < len1; j++) {
    rowIndex = rowsIndexes[j];
    if (rowIndex === range.end || rowIndex === range.end + 1) {
      range.end = rowIndex;
    } else {
      ranges.push(range);
      range = {
        start: rowIndex,
        end: rowIndex
      };
    }
  }
  ranges.push(range);
  return ranges;
}
```
- example usage
```shell
...
if (annotation.type === 'warning') {
  log = logger.warn;
} else {
  error = true;
  log = logger.error;
}
if (annotation.component === 'apiDescriptionParser') {
  ranges = blueprintUtils.warningLocationToRanges(annotation.location, apiDescriptionDocument);
  message = "Parser " + annotation.type + " in file '" + filename + "': (" + annotation.type + " code " + annotation.code + ") " +
annotation.message + " ";
  if (ranges != null ? ranges.length : void 0) {
    message += "on " + (blueprintUtils.rangesToLinesText(ranges));
  }
  log(message);
} else {
  transactionName = [annotation.origin.resourceGroupName, annotation.origin.resourceName, annotation.origin.actionName].join(' > ');
...
```



# <a name="apidoc.module.dredd.child_process"></a>[module dredd.child_process](#apidoc.module.dredd.child_process)

#### <a name="apidoc.element.dredd.child_process.signalKill"></a>[function <span class="apidocSignatureSpan">dredd.child_process.</span>signalKill (childProcess, callback)](#apidoc.element.dredd.child_process.signalKill)
- description and source-code
```javascript
signalKill = function (childProcess, callback) {
  var taskkill;
  childProcess.emit('signalKill');
  if (IS_WINDOWS) {
    taskkill = spawn('taskkill', ['/F', '/T', '/PID', childProcess.pid]);
    return taskkill.on('exit', function(exitStatus) {
      var err;
      if (exitStatus) {
        err = new Error("Unable to forcefully terminate process " + childProcess.pid);
        return callback(err);
      }
      return callback();
    });
  } else {
    childProcess.kill('SIGKILL');
    return process.nextTick(callback);
  }
}
```
- example usage
```shell
...
  return function(exitStatus) {
    logger.verbose("Exiting Dredd process with status '" + exitStatus + "'.");
    logger.debug('Using configured custom callback to terminate the Dredd process.');
    _this.finished = true;
    if (_this.sigIntEventAdded) {
      if ((_this.serverProcess != null) && !_this.serverProcess.terminated) {
        logger.verbose('Killing backend server process before Dredd exits.');
        _this.serverProcess.signalKill();
      }
      process.removeEventListener('SIGINT', _this.commandSigInt);
    }
    _this.cb(exitStatus);
    return _this;
  };
})(this);
...
```

#### <a name="apidoc.element.dredd.child_process.signalTerm"></a>[function <span class="apidocSignatureSpan">dredd.child_process.</span>signalTerm (childProcess, callback)](#apidoc.element.dredd.child_process.signalTerm)
- description and source-code
```javascript
signalTerm = function (childProcess, callback) {
  childProcess.emit('signalTerm');
  if (IS_WINDOWS) {
    childProcess.stdin.write(String.fromCharCode(ASCII_CTRL_C));
  } else {
    childProcess.kill('SIGTERM');
  }
  return process.nextTick(callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.child_process.spawn"></a>[function <span class="apidocSignatureSpan">dredd.child_process.</span>spawn ()](#apidoc.element.dredd.child_process.spawn)
- description and source-code
```javascript
spawn = function () {
  var args, childProcess, killedIntentionally, terminatedIntentionally;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  childProcess = crossSpawn.spawn.apply(null, args);
  childProcess.terminated = false;
  killedIntentionally = false;
  terminatedIntentionally = false;
  childProcess.on('signalKill', function() {
    return killedIntentionally = true;
  });
  childProcess.on('signalTerm', function() {
    return terminatedIntentionally = true;
  });
  childProcess.signalKill = function() {
    return signalKill(childProcess, function(err) {
      if (err) {
        return childProcess.emit('error', err);
      }
    });
  };
  childProcess.signalTerm = function() {
    return signalTerm(childProcess, function(err) {
      if (err) {
        return childProcess.emit('error', err);
      }
    });
  };
  childProcess.terminate = function(options) {
    return terminate(childProcess, options, function(err) {
      if (err) {
        return childProcess.emit('error', err);
      }
    });
  };
  childProcess.on('exit', function(exitStatus, signal) {
    childProcess.terminated = true;
    childProcess.killedIntentionally = killedIntentionally;
    childProcess.terminatedIntentionally = terminatedIntentionally;
    if (!killedIntentionally && !terminatedIntentionally) {
      if (signal === 'SIGKILL') {
        return childProcess.emit('crash', null, true);
      } else if (exitStatus !== 0) {
        return childProcess.emit('crash', exitStatus, false);
      }
    }
  });
  return childProcess;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.child_process.terminate"></a>[function <span class="apidocSignatureSpan">dredd.child_process.</span>terminate (childProcess, options, callback)](#apidoc.element.dredd.child_process.terminate)
- description and source-code
```javascript
terminate = function (childProcess, options, callback) {
  var check, force, onExit, ref, retryDelay, start, t, terminated, timeout;
  if (options == null) {
    options = {};
  }
  if (typeof options === 'function') {
    ref = [options, {}], callback = ref[0], options = ref[1];
  }
  force = options.force || false;
  timeout = options.timeout != null ? options.timeout : TERM_DEFAULT_TIMEOUT_MS;
  retryDelay = options.retryDelay != null ? options.retryDelay : TERM_DEFAULT_RETRY_MS;
  terminated = false;
  onExit = function() {
    terminated = true;
    return childProcess.removeListener('exit', onExit);
  };
  childProcess.on('exit', onExit);
  start = Date.now();
  t = void 0;
  check = function() {
    if (terminated) {
      clearTimeout(t);
      return callback();
    } else {
      if ((Date.now() - start) < timeout) {
        return signalTerm(childProcess, function(err) {
          if (err) {
            return callback(err);
          }
          return t = setTimeout(check, retryDelay);
        });
      } else {
        clearTimeout(t);
        if (force) {
          return signalKill(childProcess, callback);
        } else {
          return callback(new Error("Unable to gracefully terminate process " + childProcess.pid));
        }
      }
    }
  };
  return signalTerm(childProcess, function(err) {
    if (err) {
      return callback(err);
    }
    return t = setTimeout(check, TERM_FIRST_CHECK_TIMEOUT_MS);
  });
}
```
- example usage
```shell
...
    return callback();
  }
  if (this.serverProcess.terminated) {
    logger.debug('The backend server process has already terminated');
    return callback();
  }
  logger.verbose('Terminating backend server process, PID', this.serverProcess.pid);
  this.serverProcess.terminate({
    force: true
  });
  return this.serverProcess.on('exit', function() {
    return callback();
  });
};
...
```



# <a name="apidoc.module.dredd.config_utils"></a>[module dredd.config_utils](#apidoc.module.dredd.config_utils)

#### <a name="apidoc.element.dredd.config_utils.load"></a>[function <span class="apidocSignatureSpan">dredd.config_utils.</span>load (path)](#apidoc.element.dredd.config_utils.load)
- description and source-code
```javascript
load = function (path) {
  var data, yamlData;
  if (path == null) {
    path = './dredd.yml';
  }
  yamlData = fs.readFileSync(path);
  data = yaml.safeLoad(yamlData);
  data['_'] = [data['blueprint'], data['endpoint']];
  delete data['blueprint'];
  delete data['endpoint'];
  return data;
}
```
- example usage
```shell
...

  DreddCommand.prototype.loadDreddFile = function() {
var configPath, key, ref, value;
configPath = this.argv.config;
logger.verbose('Loading configuration file:', configPath);
if (configPath && fs.existsSync(configPath)) {
  logger.info("Configuration '" + configPath + "' found, ignoring other arguments.");
  this.argv = configUtils.load(configPath);
}
ref = this.cliArgv;
for (key in ref) {
  value = ref[key];
  if (key !== "_" && key !== "$0") {
    this.argv[key] = value;
  }
...
```

#### <a name="apidoc.element.dredd.config_utils.parseCustom"></a>[function <span class="apidocSignatureSpan">dredd.config_utils.</span>parseCustom (customArray)](#apidoc.element.dredd.config_utils.parseCustom)
- description and source-code
```javascript
parseCustom = function (customArray) {
  var i, len, output, splitted, string;
  output = {};
  if (Array.isArray(customArray)) {
    for (i = 0, len = customArray.length; i < len; i++) {
      string = customArray[i];
      splitted = string.split(/:(.+)?/);
      output[splitted[0]] = splitted[1];
    }
  }
  return output;
}
```
- example usage
```shell
...
      this.argv[key] = value;
    }
  }
  return this.argv = applyLoggingOptions(this.argv);
};

DreddCommand.prototype.parseCustomConfig = function() {
  return this.argv.custom = configUtils.parseCustom(this.argv.custom);
};

DreddCommand.prototype.runServerAndThenDredd = function(callback) {
  var command, parsedArgs, waitMilis, waitSecs;
  if (this.argv['server'] == null) {
    logger.verbose('No backend server process specified, starting testing at once');
    return this.runDredd(this.dreddInstance);
...
```

#### <a name="apidoc.element.dredd.config_utils.save"></a>[function <span class="apidocSignatureSpan">dredd.config_utils.</span>save (argsOrigin, path)](#apidoc.element.dredd.config_utils.save)
- description and source-code
```javascript
save = function (argsOrigin, path) {
  var args, key, value, yamlArgs;
  if (path == null) {
    path = './dredd.yml';
  }
  args = clone(argsOrigin);
  args['blueprint'] = args['_'][0];
  args['endpoint'] = args['_'][1];
  for (key in args) {
    value = args[key];
    if (key.length === 1) {
      delete args[key];
    }
  }
  delete args['$0'];
  delete args['_'];
  yamlArgs = yaml.dump(args);
  return fs.writeFileSync(path, yamlArgs);
}
```
- example usage
```shell
...

  DreddCommand.prototype.runExitingActions = function() {
if (this.argv["_"][0] === "init" || this.argv.init === true) {
  logger.silly('Starting interactive configuration.');
  this.finished = true;
  return interactiveConfig.run(this.argv, (function(_this) {
    return function(config) {
      configUtils.save(config);
      console.log("");
      console.log("Configuration saved to dredd.yml");
      console.log("");
      if (config['language'] === "nodejs") {
        console.log("Run test now, with:");
      } else {
        console.log("Install hooks handler and run Dredd test with:");
...
```



# <a name="apidoc.module.dredd.configuration"></a>[module dredd.configuration](#apidoc.module.dredd.configuration)

#### <a name="apidoc.element.dredd.configuration.applyConfiguration"></a>[function <span class="apidocSignatureSpan">dredd.configuration.</span>applyConfiguration (config)](#apidoc.element.dredd.configuration.applyConfiguration)
- description and source-code
```javascript
applyConfiguration = function (config) {
  var authHeader, configuration, customKey, customVal, key, method, ref, value;
  configuration = {
    blueprintPath: null,
    server: null,
    emitter: new EventEmitter,
    hooksCode: null,
    custom: {},
    options: {
      'dry-run': false,
      silent: false,
      reporter: null,
      output: null,
      debug: false,
      header: null,
      user: null,
      'inline-errors': false,
      details: false,
      method: [],
      only: [],
      color: true,
      level: 'info',
      timestamp: false,
      sorted: false,
      names: false,
      hookfiles: null,
      sandbox: false,
      language: 'nodejs',
      'hooks-worker-timeout': 5000,
      'hooks-worker-connect-timeout': 1500,
      'hooks-worker-connect-retry': 500,
      'hooks-worker-after-connect-wait': 100,
      'hooks-worker-term-timeout': 5000,
      'hooks-worker-term-retry': 500,
      'hooks-worker-handler-host': '127.0.0.1',
      'hooks-worker-handler-port': 61321
    }
  };
  for (key in config) {
    if (!hasProp.call(config, key)) continue;
    value = config[key];
    if (key !== 'custom') {
      configuration[key] = value;
    } else {
      if (configuration['custom'] == null) {
        configuration['custom'] = {};
      }
      ref = config['custom'] || {};
      for (customKey in ref) {
        if (!hasProp.call(ref, customKey)) continue;
        customVal = ref[customKey];
        configuration['custom'][customKey] = clone(customVal, false);
      }
    }
  }
  configuration.options.reporter = coerceToArray(configuration.options.reporter);
  configuration.options.output = coerceToArray(configuration.options.output);
  configuration.options.header = coerceToArray(configuration.options.header);
  configuration.options.method = coerceToArray(configuration.options.method);
  configuration.options.only = coerceToArray(configuration.options.only);
  configuration.options.path = coerceToArray(configuration.options.path);
  if (config.blueprintPath) {
    configuration.options.path.push(config.blueprintPath);
  }
  configuration.options.method = (function() {
    var i, len, ref1, results;
    ref1 = configuration.options.method;
    results = [];
    for (i = 0, len = ref1.length; i < len; i++) {
      method = ref1[i];
      results.push(method.toUpperCase());
    }
    return results;
  })();
  if (configuration.options.user != null) {
    authHeader = 'Authorization:Basic ' + new Buffer(configuration.options.user).toString('base64');
    configuration.options.header.push(authHeader);
  }
  configuration.options = applyLoggingOptions(configuration.options);
  return configuration;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.configuration.applyLoggingOptions"></a>[function <span class="apidocSignatureSpan">dredd.configuration.</span>applyLoggingOptions (options)](#apidoc.element.dredd.configuration.applyLoggingOptions)
- description and source-code
```javascript
applyLoggingOptions = function (options) {
  if (options.color === 'false') {
    options.color = false;
  } else if (options.color === 'true') {
    options.color = true;
  }
  logger.transports.console.colorize = options.color;
  logger.transports.console.silent = options.silent;
  logger.transports.console.timestamp = options.timestamp;
  logger.transports.console.level = options.level;
  return options;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.dredd_command"></a>[module dredd.dredd_command](#apidoc.module.dredd.dredd_command)

#### <a name="apidoc.element.dredd.dredd_command.dredd_command"></a>[function <span class="apidocSignatureSpan">dredd.</span>dredd_command (options, cb)](#apidoc.element.dredd.dredd_command.dredd_command)
- description and source-code
```javascript
function DreddCommand(options, cb) {
  if (options == null) {
    options = {};
  }
  this.cb = cb;
  this.finished = false;
  this.exit = options.exit, this.custom = options.custom;
  this.setExitOrCallback();
  if (this.custom == null) {
    this.custom = {};
  }
  if (!this.custom.cwd || typeof this.custom.cwd !== 'string') {
    this.custom.cwd = process.cwd();
  }
  if (!this.custom.argv || !Array.isArray(this.custom.argv)) {
    this.custom.argv = [];
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.dredd_command.prototype"></a>[module dredd.dredd_command.prototype](#apidoc.module.dredd.dredd_command.prototype)

#### <a name="apidoc.element.dredd.dredd_command.prototype.checkRequiredArgs"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>checkRequiredArgs ()](#apidoc.element.dredd.dredd_command.prototype.checkRequiredArgs)
- description and source-code
```javascript
checkRequiredArgs = function () {
  var argError;
  argError = false;
  if (this.argv._[0] == null) {
    console.error("\nError: Must specify path to API description document.");
    argError = true;
  }
  if (this.argv._[1] == null) {
    console.error("\nError: Must specify URL of the tested API instance.");
    argError = true;
  }
  if (argError) {
    console.error("\n");
    this.optimist.showHelp(console.error);
    return this._processExit(1);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.commandSigInt"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>commandSigInt ()](#apidoc.element.dredd.dredd_command.prototype.commandSigInt)
- description and source-code
```javascript
commandSigInt = function () {
  logger.error('\nShutting down from keyboard interruption (Ctrl+C)');
  return this.dreddInstance.transactionsComplete((function(_this) {
    return function() {
      return _this._processExit(0);
    };
  })(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.exitWithStatus"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>exitWithStatus (error, stats)](#apidoc.element.dredd.dredd_command.prototype.exitWithStatus)
- description and source-code
```javascript
exitWithStatus = function (error, stats) {
  if (error) {
    if (error.message) {
      logger.error(error.message);
    }
    return this._processExit(1);
  }
  if ((stats.failures + stats.errors) > 0) {
    this._processExit(1);
  } else {
    this._processExit(0);
  }
}
```
- example usage
```shell
...
    this.sigIntEventAdded = !(this.sigIntEventAdd = false);
    process.on('SIGINT', this.commandSigInt);
  }
  logger.verbose('Running Dredd instance.');
  dreddInstance.run((function(_this) {
    return function(error, stats) {
      logger.verbose('Dredd instance run finished.');
      return _this.exitWithStatus(error, stats);
    };
  })(this));
  return this;
};

DreddCommand.prototype.exitWithStatus = function(error, stats) {
  if (error) {
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.initConfig"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>initConfig ()](#apidoc.element.dredd.dredd_command.prototype.initConfig)
- description and source-code
```javascript
initConfig = function () {
  var base, configuration;
  this.lastArgvIsApiEndpoint().takeRestOfParamsAsPath();
  configuration = {
    'server': this.server,
    'options': this.argv
  };
  if ((base = configuration.options).path == null) {
    base.path = [];
  }
  configuration.options.path.push(this.argv._[0]);
  configuration.custom = this.custom;
  return configuration;
}
```
- example usage
```shell
...
for (i = 0, len = ref.length; i < len; i++) {
  task = ref[i];
  task.call(this);
  if (this.finished) {
    return;
  }
}
configurationForDredd = this.initConfig();
this.logDebuggingInfo(configurationForDredd);
this.dreddInstance = this.initDredd(configurationForDredd);
try {
  this.runServerAndThenDredd();
} catch (error1) {
  e = error1;
  logger.error(e.message, e.stack);
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.initDredd"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>initDredd (configuration)](#apidoc.element.dredd.dredd_command.prototype.initDredd)
- description and source-code
```javascript
initDredd = function (configuration) {
  return new Dredd(configuration);
}
```
- example usage
```shell
...
  task.call(this);
  if (this.finished) {
    return;
  }
}
configurationForDredd = this.initConfig();
this.logDebuggingInfo(configurationForDredd);
this.dreddInstance = this.initDredd(configurationForDredd);
try {
  this.runServerAndThenDredd();
} catch (error1) {
  e = error1;
  logger.error(e.message, e.stack);
  this.stopServer((function(_this) {
    return function() {
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.lastArgvIsApiEndpoint"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>lastArgvIsApiEndpoint ()](#apidoc.element.dredd.dredd_command.prototype.lastArgvIsApiEndpoint)
- description and source-code
```javascript
lastArgvIsApiEndpoint = function () {
  this.server = this.argv._[this.argv._.length - 1];
  this.argv._.splice(this.argv._.length - 1, 1);
  return this;
}
```
- example usage
```shell
...
DreddCommand.prototype.takeRestOfParamsAsPath = function() {
  this.argv['p'] = this.argv['path'] = this.argv['path'].concat(this.argv._);
  return this;
};

DreddCommand.prototype.initConfig = function() {
  var base, configuration;
  this.lastArgvIsApiEndpoint().takeRestOfParamsAsPath();
  configuration = {
    'server': this.server,
    'options': this.argv
  };
  if ((base = configuration.options).path == null) {
    base.path = [];
  }
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.loadDreddFile"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>loadDreddFile ()](#apidoc.element.dredd.dredd_command.prototype.loadDreddFile)
- description and source-code
```javascript
loadDreddFile = function () {
  var configPath, key, ref, value;
  configPath = this.argv.config;
  logger.verbose('Loading configuration file:', configPath);
  if (configPath && fs.existsSync(configPath)) {
    logger.info("Configuration '" + configPath + "' found, ignoring other arguments.");
    this.argv = configUtils.load(configPath);
  }
  ref = this.cliArgv;
  for (key in ref) {
    value = ref[key];
    if (key !== "_" && key !== "$0") {
      this.argv[key] = value;
    }
  }
  return this.argv = applyLoggingOptions(this.argv);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.logDebuggingInfo"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>logDebuggingInfo (config)](#apidoc.element.dredd.dredd_command.prototype.logDebuggingInfo)
- description and source-code
```javascript
logDebuggingInfo = function (config) {
  var err, npmVersion;
  logger.debug('Dredd version:', packageData.version);
  logger.debug('Node.js version:', process.version);
  logger.debug('Node.js environment:', process.versions);
  logger.debug('System version:', os.type(), os.release(), os.arch());
  try {
    npmVersion = spawnSync('npm', ['--version']).stdout.toString().trim();
    logger.debug('npm version:', npmVersion || 'unable to determine npm version');
  } catch (error1) {
    err = error1;
    logger.debug('npm version: unable to determine npm version:', err);
  }
  return logger.debug('Configuration:', JSON.stringify(config));
}
```
- example usage
```shell
...
  task = ref[i];
  task.call(this);
  if (this.finished) {
    return;
  }
}
configurationForDredd = this.initConfig();
this.logDebuggingInfo(configurationForDredd);
this.dreddInstance = this.initDredd(configurationForDredd);
try {
  this.runServerAndThenDredd();
} catch (error1) {
  e = error1;
  logger.error(e.message, e.stack);
  this.stopServer((function(_this) {
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.moveBlueprintArgToPath"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>moveBlueprintArgToPath ()](#apidoc.element.dredd.dredd_command.prototype.moveBlueprintArgToPath)
- description and source-code
```javascript
moveBlueprintArgToPath = function () {
  if (!Array.isArray(this.argv['path'])) {
    return this.argv['path'] = this.argv['p'] = [this.argv['path']];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.parseCustomConfig"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>parseCustomConfig ()](#apidoc.element.dredd.dredd_command.prototype.parseCustomConfig)
- description and source-code
```javascript
parseCustomConfig = function () {
  return this.argv.custom = configUtils.parseCustom(this.argv.custom);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.run"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>run ()](#apidoc.element.dredd.dredd_command.prototype.run)
- description and source-code
```javascript
run = function () {
  var configurationForDredd, e, i, len, ref, task;
  ref = [this.setOptimistArgv, this.parseCustomConfig, this.runExitingActions, this.loadDreddFile, this.checkRequiredArgs, this.
moveBlueprintArgToPath];
  for (i = 0, len = ref.length; i < len; i++) {
    task = ref[i];
    task.call(this);
    if (this.finished) {
      return;
    }
  }
  configurationForDredd = this.initConfig();
  this.logDebuggingInfo(configurationForDredd);
  this.dreddInstance = this.initDredd(configurationForDredd);
  try {
    this.runServerAndThenDredd();
  } catch (error1) {
    e = error1;
    logger.error(e.message, e.stack);
    this.stopServer((function(_this) {
      return function() {
        return _this._processExit(2);
      };
    })(this));
  }
}
```
- example usage
```shell
...
  }
};

DreddCommand.prototype.runExitingActions = function() {
  if (this.argv["_"][0] === "init" || this.argv.init === true) {
    logger.silly('Starting interactive configuration.');
    this.finished = true;
    return interactiveConfig.run(this.argv, (function(_this) {
      return function(config) {
        configUtils.save(config);
        console.log("");
        console.log("Configuration saved to dredd.yml");
        console.log("");
        if (config['language'] === "nodejs") {
          console.log("Run test now, with:");
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.runDredd"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runDredd (dreddInstance)](#apidoc.element.dredd.dredd_command.prototype.runDredd)
- description and source-code
```javascript
runDredd = function (dreddInstance) {
  if (this.sigIntEventAdd) {
    this.sigIntEventAdded = !(this.sigIntEventAdd = false);
    process.on('SIGINT', this.commandSigInt);
  }
  logger.verbose('Running Dredd instance.');
  dreddInstance.run((function(_this) {
    return function(error, stats) {
      logger.verbose('Dredd instance run finished.');
      return _this.exitWithStatus(error, stats);
    };
  })(this));
  return this;
}
```
- example usage
```shell
...
  return this.argv.custom = configUtils.parseCustom(this.argv.custom);
};

DreddCommand.prototype.runServerAndThenDredd = function(callback) {
  var command, parsedArgs, waitMilis, waitSecs;
  if (this.argv['server'] == null) {
    logger.verbose('No backend server process specified, starting testing at once');
    return this.runDredd(this.dreddInstance);
  } else {
    logger.verbose('Backend server process specified, starting backend server and then testing');
    parsedArgs = spawnArgs(this.argv['server']);
    command = parsedArgs.shift();
    logger.verbose("Using '" + command + "' as a server command, " + (JSON.stringify(parsedArgs)) + " as arguments");
    this.serverProcess = spawn(command, parsedArgs);
    logger.info("Starting backend server process with command: " + this.argv['server']);
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.runExitingActions"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runExitingActions ()](#apidoc.element.dredd.dredd_command.prototype.runExitingActions)
- description and source-code
```javascript
runExitingActions = function () {
  if (this.argv["_"][0] === "init" || this.argv.init === true) {
    logger.silly('Starting interactive configuration.');
    this.finished = true;
    return interactiveConfig.run(this.argv, (function(_this) {
      return function(config) {
        configUtils.save(config);
        console.log("");
        console.log("Configuration saved to dredd.yml");
        console.log("");
        if (config['language'] === "nodejs") {
          console.log("Run test now, with:");
        } else {
          console.log("Install hooks handler and run Dredd test with:");
        }
        console.log("");
        if (config['language'] === 'ruby') {
          console.log("  $ gem install dredd_hooks");
        } else if (config['language'] === 'python') {
          console.log("  $ pip install dredd_hooks");
        } else if (config['language'] === 'php') {
          console.log("  $ composer require ddelnano/dredd-hooks-php --dev");
        } else if (config['language'] === 'perl') {
          console.log("  $ cpanm Dredd::Hooks");
        } else if (config['language'] === 'go') {
          console.log("  $ go get github.com/snikch/goodman/cmd/goodman");
        }
        console.log("  $ dredd");
        console.log("");
        return _this._processExit(0);
      };
    })(this));
  } else if (this.argv.help === true) {
    logger.silly('Printing help.');
    this.optimist.showHelp(console.error);
    return this._processExit(0);
  } else if (this.argv.version === true) {
    logger.silly('Printing version.');
    console.log(packageData.name + " v" + packageData.version + " (" + (os.type()) + " " + (os.release()) + "; " + (os.arch()) + ")");
    return this._processExit(0);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.runServerAndThenDredd"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>runServerAndThenDredd (callback)](#apidoc.element.dredd.dredd_command.prototype.runServerAndThenDredd)
- description and source-code
```javascript
runServerAndThenDredd = function (callback) {
  var command, parsedArgs, waitMilis, waitSecs;
  if (this.argv['server'] == null) {
    logger.verbose('No backend server process specified, starting testing at once');
    return this.runDredd(this.dreddInstance);
  } else {
    logger.verbose('Backend server process specified, starting backend server and then testing');
    parsedArgs = spawnArgs(this.argv['server']);
    command = parsedArgs.shift();
    logger.verbose("Using '" + command + "' as a server command, " + (JSON.stringify(parsedArgs)) + " as arguments");
    this.serverProcess = spawn(command, parsedArgs);
    logger.info("Starting backend server process with command: " + this.argv['server']);
    this.serverProcess.stdout.setEncoding('utf8');
    this.serverProcess.stdout.on('data', function(data) {
      return process.stdout.write(data.toString());
    });
    this.serverProcess.stderr.setEncoding('utf8');
    this.serverProcess.stderr.on('data', function(data) {
      return process.stdout.write(data.toString());
    });
    this.serverProcess.on('signalTerm', function() {
      return logger.verbose('Gracefully terminating the backend server process');
    });
    this.serverProcess.on('signalKill', function() {
      return logger.verbose('Killing the backend server process');
    });
    this.serverProcess.on('crash', (function(_this) {
      return function(exitStatus, killed) {
        if (killed) {
          return logger.info('Backend server process was killed');
        }
      };
    })(this));
    this.serverProcess.on('exit', (function(_this) {
      return function() {
        return logger.info('Backend server process exited');
      };
    })(this));
    this.serverProcess.on('error', (function(_this) {
      return function(error) {
        logger.error('Command to start backend server process failed, exiting Dredd', error);
        return _this._processExit(2);
      };
    })(this));
    process.on('beforeExit', (function(_this) {
      return function() {
        if ((_this.serverProcess != null) && !_this.serverProcess.terminated) {
          logger.verbose('Killing backend server process before Dredd exits');
          return _this.serverProcess.signalKill();
        }
      };
    })(this));
    process.on('exit', (function(_this) {
      return function() {
        if ((_this.serverProcess != null) && !_this.serverProcess.terminated) {
          logger.verbose('Killing backend server process on Dredd\'s exit');
          return _this.serverProcess.signalKill();
        }
      };
    })(this));
    waitSecs = parseInt(this.argv['server-wait'], 10);
    waitMilis = waitSecs * 1000;
    logger.info("Waiting " + waitSecs + " seconds for backend server process to start");
    return this.wait = setTimeout((function(_this) {
      return function() {
        return _this.runDredd(_this.dreddInstance);
      };
    })(this), waitMilis);
  }
}
```
- example usage
```shell
...
    return;
  }
}
configurationForDredd = this.initConfig();
this.logDebuggingInfo(configurationForDredd);
this.dreddInstance = this.initDredd(configurationForDredd);
try {
  this.runServerAndThenDredd();
} catch (error1) {
  e = error1;
  logger.error(e.message, e.stack);
  this.stopServer((function(_this) {
    return function() {
      return _this._processExit(2);
    };
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.setExitOrCallback"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>setExitOrCallback ()](#apidoc.element.dredd.dredd_command.prototype.setExitOrCallback)
- description and source-code
```javascript
setExitOrCallback = function () {
  if (!this.cb) {
    if (this.exit && (this.exit === process.exit)) {
      this.sigIntEventAdd = true;
    }
    if (this.exit) {
      return this._processExit = (function(_this) {
        return function(exitStatus) {
          logger.verbose("Exiting Dredd process with status '" + exitStatus + "'.");
          logger.debug('Using configured custom exit() method to terminate the Dredd process.');
          _this.finished = true;
          return _this.stopServer(function() {
            return _this.exit(exitStatus);
          });
        };
      })(this);
    } else {
      return this._processExit = (function(_this) {
        return function(exitStatus) {
          logger.verbose("Exiting Dredd process with status '" + exitStatus + "'.");
          logger.debug('Using native process.exit() method to terminate the Dredd process.');
          return _this.stopServer(function() {
            return process.exit(exitStatus);
          });
        };
      })(this);
    }
  } else {
    return this._processExit = (function(_this) {
      return function(exitStatus) {
        logger.verbose("Exiting Dredd process with status '" + exitStatus + "'.");
        logger.debug('Using configured custom callback to terminate the Dredd process.');
        _this.finished = true;
        if (_this.sigIntEventAdded) {
          if ((_this.serverProcess != null) && !_this.serverProcess.terminated) {
            logger.verbose('Killing backend server process before Dredd exits.');
            _this.serverProcess.signalKill();
          }
          process.removeEventListener('SIGINT', _this.commandSigInt);
        }
        _this.cb(exitStatus);
        return _this;
      };
    })(this);
  }
}
```
- example usage
```shell
...
  function DreddCommand(options, cb) {
if (options == null) {
  options = {};
}
this.cb = cb;
this.finished = false;
this.exit = options.exit, this.custom = options.custom;
this.setExitOrCallback();
if (this.custom == null) {
  this.custom = {};
}
if (!this.custom.cwd || typeof this.custom.cwd !== 'string') {
  this.custom.cwd = process.cwd();
}
if (!this.custom.argv || !Array.isArray(this.custom.argv)) {
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.setOptimistArgv"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>setOptimistArgv ()](#apidoc.element.dredd.dredd_command.prototype.setOptimistArgv)
- description and source-code
```javascript
setOptimistArgv = function () {
  this.optimist = optimist(this.custom.argv, this.custom.cwd);
  this.cliArgv = this.optimist.argv;
  this.optimist.usage('Usage:\n  $ dredd init\n\nOr:\n  $ dredd <path or URL to API description document> <URL of tested server> [
OPTIONS]\n\nExample:\n  $ dredd ./api-description.apib http://127.0.0.1:3000 --dry-run').options(Dredd.options).wrap(80);
  this.argv = this.optimist.argv;
  return this.argv = applyLoggingOptions(this.argv);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.stopServer"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>stopServer (callback)](#apidoc.element.dredd.dredd_command.prototype.stopServer)
- description and source-code
```javascript
stopServer = function (callback) {
  if (this.serverProcess == null) {
    logger.verbose('No backend server process to terminate.');
    return callback();
  }
  if (this.serverProcess.terminated) {
    logger.debug('The backend server process has already terminated');
    return callback();
  }
  logger.verbose('Terminating backend server process, PID', this.serverProcess.pid);
  this.serverProcess.terminate({
    force: true
  });
  return this.serverProcess.on('exit', function() {
    return callback();
  });
}
```
- example usage
```shell
...
}
if (this.exit) {
  return this._processExit = (function(_this) {
    return function(exitStatus) {
      logger.verbose("Exiting Dredd process with status '" + exitStatus + "'.");
      logger.debug('Using configured custom exit() method to terminate the Dredd process.');
      _this.finished = true;
      return _this.stopServer(function() {
        return _this.exit(exitStatus);
      });
    };
  })(this);
} else {
  return this._processExit = (function(_this) {
    return function(exitStatus) {
...
```

#### <a name="apidoc.element.dredd.dredd_command.prototype.takeRestOfParamsAsPath"></a>[function <span class="apidocSignatureSpan">dredd.dredd_command.prototype.</span>takeRestOfParamsAsPath ()](#apidoc.element.dredd.dredd_command.prototype.takeRestOfParamsAsPath)
- description and source-code
```javascript
takeRestOfParamsAsPath = function () {
  this.argv['p'] = this.argv['path'] = this.argv['path'].concat(this.argv._);
  return this;
}
```
- example usage
```shell
...
DreddCommand.prototype.takeRestOfParamsAsPath = function() {
  this.argv['p'] = this.argv['path'] = this.argv['path'].concat(this.argv._);
  return this;
};

DreddCommand.prototype.initConfig = function() {
  var base, configuration;
  this.lastArgvIsApiEndpoint().takeRestOfParamsAsPath();
  configuration = {
    'server': this.server,
    'options': this.argv
  };
  if ((base = configuration.options).path == null) {
    base.path = [];
  }
...
```



# <a name="apidoc.module.dredd.hooks"></a>[module dredd.hooks](#apidoc.module.dredd.hooks)

#### <a name="apidoc.element.dredd.hooks.hooks"></a>[function <span class="apidocSignatureSpan">dredd.</span>hooks (options)](#apidoc.element.dredd.hooks.hooks)
- description and source-code
```javascript
function Hooks(options) {
  if (options == null) {
    options = {};
  }
  this.dumpHooksFunctionsToStrings = bind(this.dumpHooksFunctionsToStrings, this);
  this.log = bind(this.log, this);
  this.afterEach = bind(this.afterEach, this);
  this.beforeEachValidation = bind(this.beforeEachValidation, this);
  this.beforeEach = bind(this.beforeEach, this);
  this.afterAll = bind(this.afterAll, this);
  this.beforeAll = bind(this.beforeAll, this);
  this.after = bind(this.after, this);
  this.beforeValidation = bind(this.beforeValidation, this);
  this.before = bind(this.before, this);
  this.logs = options.logs, this.logger = options.logger;
  this.transactions = {};
  this.beforeHooks = {};
  this.beforeValidationHooks = {};
  this.afterHooks = {};
  this.beforeAllHooks = [];
  this.afterAllHooks = [];
  this.beforeEachHooks = [];
  this.beforeEachValidationHooks = [];
  this.afterEachHooks = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.hooks.prototype"></a>[module dredd.hooks.prototype](#apidoc.module.dredd.hooks.prototype)

#### <a name="apidoc.element.dredd.hooks.prototype.addHook"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>addHook (hooks, name, hook)](#apidoc.element.dredd.hooks.prototype.addHook)
- description and source-code
```javascript
addHook = function (hooks, name, hook) {
  if (hooks[name]) {
    return hooks[name].push(hook);
  } else {
    return hooks[name] = [hook];
  }
}
```
- example usage
```shell
...
  this.afterAllHooks = [];
  this.beforeEachHooks = [];
  this.beforeEachValidationHooks = [];
  this.afterEachHooks = [];
}

Hooks.prototype.before = function(name, hook) {
  return this.addHook(this.beforeHooks, name, hook);
};

Hooks.prototype.beforeValidation = function(name, hook) {
  return this.addHook(this.beforeValidationHooks, name, hook);
};

Hooks.prototype.after = function(name, hook) {
...
```

#### <a name="apidoc.element.dredd.hooks.prototype.after"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>after (name, hook)](#apidoc.element.dredd.hooks.prototype.after)
- description and source-code
```javascript
after = function (name, hook) {
  return this.addHook(this.afterHooks, name, hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.afterAll"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>afterAll (hook)](#apidoc.element.dredd.hooks.prototype.afterAll)
- description and source-code
```javascript
afterAll = function (hook) {
  return this.afterAllHooks.push(hook);
}
```
- example usage
```shell
...
    });
  };
})(this);
for (i = 0, len = eachHookNames.length; i < len; i++) {
  eventName = eachHookNames[i];
  fn(eventName);
}
this.runner.hooks.afterAll((function(_this) {
  return function(transactions, hookCallback) {
    var index, j, len1, modification, modifications, ref;
    if (process.env.TEST_DREDD_HOOKS_HANDLER_ORDER === 'true') {
      console.error('FOR TESTING ONLY');
      modifications = ((ref = transactions[0]) != null ? ref.hooks_modifications : void 0) || [];
      if (!modifications.length) {
        throw new Error('Hooks must modify transaction.hooks_modifications');
...
```

#### <a name="apidoc.element.dredd.hooks.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>afterEach (hook)](#apidoc.element.dredd.hooks.prototype.afterEach)
- description and source-code
```javascript
afterEach = function (hook) {
  return this.afterEachHooks.push(hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.before"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>before (name, hook)](#apidoc.element.dredd.hooks.prototype.before)
- description and source-code
```javascript
before = function (name, hook) {
  return this.addHook(this.beforeHooks, name, hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.beforeAll"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeAll (hook)](#apidoc.element.dredd.hooks.prototype.beforeAll)
- description and source-code
```javascript
beforeAll = function (hook) {
  return this.beforeAllHooks.push(hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeEach (hook)](#apidoc.element.dredd.hooks.prototype.beforeEach)
- description and source-code
```javascript
beforeEach = function (hook) {
  return this.beforeEachHooks.push(hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.beforeEachValidation"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeEachValidation (hook)](#apidoc.element.dredd.hooks.prototype.beforeEachValidation)
- description and source-code
```javascript
beforeEachValidation = function (hook) {
  return this.beforeEachValidationHooks.push(hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.beforeValidation"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>beforeValidation (name, hook)](#apidoc.element.dredd.hooks.prototype.beforeValidation)
- description and source-code
```javascript
beforeValidation = function (name, hook) {
  return this.addHook(this.beforeValidationHooks, name, hook);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.hooks.prototype.dumpHooksFunctionsToStrings"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>dumpHooksFunctionsToStrings ()](#apidoc.element.dredd.hooks.prototype.dumpHooksFunctionsToStrings)
- description and source-code
```javascript
dumpHooksFunctionsToStrings = function () {
  var funcArray, hookFunc, i, index, len, names, property, ref, ref1, toReturn, transactionName;
  toReturn = {};
  names = ['beforeHooks', 'beforeValidationHooks', 'afterHooks', 'beforeAllHooks', 'afterAllHooks', 'beforeEachHooks', 'beforeEachValidationHooks
', 'afterEachHooks'];
  for (i = 0, len = names.length; i < len; i++) {
    property = names[i];
    if (Array.isArray(this[property])) {
      toReturn[property] = [];
      ref = this[property];
      for (index in ref) {
        hookFunc = ref[index];
        toReturn[property][index] = hookFunc.toString();
      }
    } else if (typeof this[property] === 'object' && !Array.isArray(this[property])) {
      toReturn[property] = {};
      ref1 = this[property];
      for (transactionName in ref1) {
        funcArray = ref1[transactionName];
        if (!funcArray.length) {
          continue;
        }
        toReturn[property][transactionName] = [];
        for (index in funcArray) {
          hookFunc = funcArray[index];
          toReturn[property][transactionName][index] = hookFunc.toString();
        }
      }
    }
  }
  return toReturn;
}
```
- example usage
```shell
...
Pitboss = require('pitboss-ng').Pitboss;

Hooks = require('./hooks');

sandboxHooksCode = function(hooksCode, callback) {
var hooks, sandbox, wrappedCode;
hooks = new Hooks();
wrappedCode = "var _hooks = new _Hooks();\n\nvar before = _hooks.before;\nvar after = _hooks.after;\nvar beforeAll = _hooks.beforeAll
;\nvar afterAll = _hooks.afterAll;\nvar beforeEach = _hooks.beforeEach;\nvar afterEach = _hooks.afterEach;\nvar beforeValidation = _hooks.beforeValidation;\nvar beforeEachValidation = _hooks.beforeEachValidation;\n\nvar log = _hooks.log;\n\n" + hooksCode + "\ntry {\n  var output = _hooks.dumpHooksFunctionsToStrings();\n} catch(e) {\n  console.log(e.message);\n  console.log(e.stack);\n  throw(e);\n}\n\noutput";
sandbox = new Pitboss(wrappedCode);
sandbox.run({
  libraries: {
    '_Hooks': '../../../lib/hooks',
    'console': 'console'
  }
}, function(err, result) {
...
```

#### <a name="apidoc.element.dredd.hooks.prototype.log"></a>[function <span class="apidocSignatureSpan">dredd.hooks.prototype.</span>log ()](#apidoc.element.dredd.hooks.prototype.log)
- description and source-code
```javascript
log = function () {
  var args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  this.logs = hooksLog.apply(null, [this.logs, this.logger].concat(slice.call(args)));
}
```
- example usage
```shell
...
  } catch (error1) {
    error = error1;
    return logger.warn("Skipping hook loading. Error reading hook file '" + filePath + "'. This probably means one or more of your
 hook files are invalid.\nMessage: " + error.message + "\nStack: " + error.stack);
  }
};
loadSandboxHooksFromStrings = function(callback) {
  if (typeof runner.configuration.hooksData !== 'object' || Array.isArray(runner.configuration.hooksData) !== false) {
    return callback(new Error("hooksData option must be an object e.g. {'filename.js':'console.log(\"Hey!\")'}"));
  }
  return async.eachSeries(Object.keys(runner.configuration.hooksData), function(key, nextHook) {
    var data;
    data = runner.configuration.hooksData[key];
    return sandboxHooksCode(data, function(sandboxError, result) {
      if (sandboxError) {
        return nextHook(sandboxError);
...
```



# <a name="apidoc.module.dredd.hooks_worker_client"></a>[module dredd.hooks_worker_client](#apidoc.module.dredd.hooks_worker_client)

#### <a name="apidoc.element.dredd.hooks_worker_client.hooks_worker_client"></a>[function <span class="apidocSignatureSpan">dredd.</span>hooks_worker_client (runner)](#apidoc.element.dredd.hooks_worker_client.hooks_worker_client)
- description and source-code
```javascript
function HooksWorkerClient(runner) {
  var options;
  this.runner = runner;
  options = this.runner.hooks.configuration.options;
  this.language = options.language;
  this.timeout = options['hooks-worker-timeout'] || 5000;
  this.connectTimeout = options['hooks-worker-connect-timeout'] || 1500;
  this.connectRetry = options['hooks-worker-connect-retry'] || 500;
  this.afterConnectWait = options['hooks-worker-after-connect-wait'] || 100;
  this.termTimeout = options['hooks-worker-term-timeout'] || 5000;
  this.termRetry = options['hooks-worker-term-retry'] || 500;
  this.handlerHost = options['hooks-worker-handler-host'] || '127.0.0.1';
  this.handlerPort = options['hooks-worker-handler-port'] || 61321;
  this.handlerMessageDelimiter = '\n';
  this.clientConnected = false;
  this.connectError = false;
  this.emitter = new EventEmitter;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.hooks_worker_client.prototype"></a>[module dredd.hooks_worker_client.prototype](#apidoc.module.dredd.hooks_worker_client.prototype)

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.connectToHandler"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>connectToHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.connectToHandler)
- description and source-code
```javascript
connectToHandler = function (callback) {
  var connectAndSetupClient, start, timeout, waitForConnect;
  start = Date.now();
  waitForConnect = (function(_this) {
    return function() {
      var error, msg, timeout;
      if ((Date.now() - start) < _this.connectTimeout) {
        clearTimeout(timeout);
        if (_this.connectError !== false) {
          logger.warn('Error connecting to the hooks handler process. Is the handler running? Retrying.');
          _this.connectError = false;
        }
        if (_this.clientConnected !== true) {
          connectAndSetupClient();
          return timeout = setTimeout(waitForConnect, _this.connectRetry);
        }
      } else {
        clearTimeout(timeout);
        if (!_this.clientConnected) {
          if (_this.handlerClient != null) {
            _this.handlerClient.destroy();
          }
          msg = ("Connection timeout " + (_this.connectTimeout / 1000) + "s to hooks handler ") + ("on " + _this.handlerHost + ":" +
_this.handlerPort + " exceeded. Try increasing the limit.");
          error = new Error(msg);
          return callback(error);
        }
      }
    };
  })(this);
  connectAndSetupClient = (function(_this) {
    return function() {
      var handlerBuffer;
      logger.verbose('Starting TCP connection with hooks handler process.');
      if (_this.runner.hookHandlerError != null) {
        return callback(_this.runner.hookHandlerError);
      }
      _this.handlerClient = net.connect({
        port: _this.handlerPort,
        host: _this.handlerHost
      });
      _this.handlerClient.on('connect', function() {
        logger.info("Successfully connected to hooks handler. Waiting " + (_this.afterConnectWait / 1000) + "s to start testing.");
        _this.clientConnected = true;
        clearTimeout(timeout);
        return setTimeout(callback, _this.afterConnectWait);
      });
      _this.handlerClient.on('close', function() {
        return logger.debug('TCP communication with hooks handler closed.');
      });
      _this.handlerClient.on('error', function(connectError) {
        logger.debug('TCP communication with hooks handler errored.', connectError);
        return _this.connectError = connectError;
      });
      handlerBuffer = '';
      return _this.handlerClient.on('data', function(data) {
        var i, j, len, len1, message, messages, results, splittedData;
        logger.debug('Dredd received some data from hooks handler.');
        handlerBuffer += data.toString();
        if (data.toString().indexOf(_this.handlerMessageDelimiter) > -1) {
          splittedData = handlerBuffer.split(_this.handlerMessageDelimiter);
          handlerBuffer = splittedData.pop();
          messages = [];
          for (i = 0, len = splittedData.length; i < len; i++) {
            message = splittedData[i];
            messages.push(JSON.parse(message));
          }
          results = [];
          for (j = 0, len1 = messages.length; j < len1; j++) {
            message = messages[j];
            if (message.uuid != null) {
              logger.verbose('Dredd received a valid message from hooks handler:', message.uuid);
              results.push(_this.emitter.emit(message.uuid, message));
            } else {
              results.push(logger.verbose('UUID not present in hooks handler message, ignoring:', JSON.stringify(message, null,
2)));
            }
          }
          return results;
        }
      });
    };
  })(this);
  return timeout = setTimeout(waitForConnect, this.connectRetry);
}
```
- example usage
```shell
...
}
logger.verbose('Starting hooks handler.');
return _this.spawnHandler(function(spawnHandlerError) {
  if (spawnHandlerError) {
    return callback(spawnHandlerError);
  }
  logger.verbose('Connecting to hooks handler.');
  return _this.connectToHandler(function(connectHandlerError) {
    if (connectHandlerError) {
      return callback(connectHandlerError);
    }
    logger.verbose('Registering hooks.');
    return _this.registerHooks(function(registerHooksError) {
      if (registerHooksError) {
        return callback(registerHooksError);
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.disconnectFromHandler"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>disconnectFromHandler ()](#apidoc.element.dredd.hooks_worker_client.prototype.disconnectFromHandler)
- description and source-code
```javascript
disconnectFromHandler = function () {
  return this.handlerClient.destroy();
}
```
- example usage
```shell
...
        });
      });
    };
  })(this));
};

HooksWorkerClient.prototype.stop = function(callback) {
  this.disconnectFromHandler();
  return this.terminateHandler(callback);
};

HooksWorkerClient.prototype.terminateHandler = function(callback) {
  logger.verbose('Terminating hooks handler process, PID', this.handler.pid);
  if (this.handler.terminated) {
    logger.debug('The hooks handler process has already terminated');
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.registerHooks"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>registerHooks (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.registerHooks)
- description and source-code
```javascript
registerHooks = function (callback) {
  var eachHookNames, eventName, fn, i, len;
  eachHookNames = ['beforeEach', 'beforeEachValidation', 'afterEach', 'beforeAll', 'afterAll'];
  fn = (function(_this) {
    return function(eventName) {
      return _this.runner.hooks[eventName](function(data, hookCallback) {
        var handleTimeout, message, messageHandler, timeout, uuid;
        uuid = generateUuid();
        message = {
          event: eventName,
          uuid: uuid,
          data: data
        };
        logger.verbose('Sending HTTP transaction data to hooks handler:', uuid);
        _this.handlerClient.write(JSON.stringify(message));
        _this.handlerClient.write(_this.handlerMessageDelimiter);
        messageHandler = function(receivedMessage) {
          var index, j, key, len1, ref, ref1, value;
          logger.verbose('Handling hook:', uuid);
          clearTimeout(timeout);
          if (eventName.indexOf('All') > -1) {
            ref = receivedMessage.data;
            for (index = j = 0, len1 = ref.length; j < len1; index = ++j) {
              value = ref[index];
              data[index] = value;
            }
          } else {
            ref1 = receivedMessage.data;
            for (key in ref1) {
              if (!hasProp.call(ref1, key)) continue;
              value = ref1[key];
              data[key] = value;
            }
          }
          return hookCallback();
        };
        handleTimeout = function() {
          logger.warn('Hook handling timed out.');
          if (eventName.indexOf('All') === -1) {
            data.fail = 'Hook timed out.';
          }
          _this.emitter.removeListener(uuid, messageHandler);
          return hookCallback();
        };
        timeout = setTimeout(handleTimeout, _this.timeout);
        return _this.emitter.on(uuid, messageHandler);
      });
    };
  })(this);
  for (i = 0, len = eachHookNames.length; i < len; i++) {
    eventName = eachHookNames[i];
    fn(eventName);
  }
  this.runner.hooks.afterAll((function(_this) {
    return function(transactions, hookCallback) {
      var index, j, len1, modification, modifications, ref;
      if (process.env.TEST_DREDD_HOOKS_HANDLER_ORDER === 'true') {
        console.error('FOR TESTING ONLY');
        modifications = ((ref = transactions[0]) != null ? ref.hooks_modifications : void 0) || [];
        if (!modifications.length) {
          throw new Error('Hooks must modify transaction.hooks_modifications');
        }
        for (index = j = 0, len1 = modifications.length; j < len1; index = ++j) {
          modification = modifications[index];
          console.error(index + " " + modification);
        }
        console.error('FOR TESTING ONLY');
      }
      return _this.stop(hookCallback);
    };
  })(this));
  return callback();
}
```
- example usage
```shell
...
  }
  logger.verbose('Connecting to hooks handler.');
  return _this.connectToHandler(function(connectHandlerError) {
    if (connectHandlerError) {
      return callback(connectHandlerError);
    }
    logger.verbose('Registering hooks.');
    return _this.registerHooks(function(registerHooksError) {
      if (registerHooksError) {
        return callback(registerHooksError);
      }
      return callback();
    });
  });
});
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.setCommandAndCheckForExecutables"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>setCommandAndCheckForExecutables (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.setCommandAndCheckForExecutables)
- description and source-code
```javascript
setCommandAndCheckForExecutables = function (callback) {
  var gobin, msg, parsedArgs;
  if (this.language === 'ruby') {
    this.handlerCommand = 'dredd-hooks-ruby';
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = "Ruby hooks handler command not found: " + this.handlerCommand + "\nInstall ruby hooks handler by running:\n$ gem install
 dredd_hooks";
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else if (this.language === 'python') {
    this.handlerCommand = 'dredd-hooks-python';
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = "Python hooks handler command not found: " + this.handlerCommand + "\nInstall python hooks handler by running:\n$ pip
 install dredd_hooks";
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else if (this.language === 'php') {
    this.handlerCommand = 'dredd-hooks-php';
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = "PHP hooks handler command not found: " + this.handlerCommand + "\nInstall php hooks handler by running:\n$ composer
 require ddelnano/dredd-hooks-php --dev";
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else if (this.language === 'perl') {
    this.handlerCommand = 'dredd-hooks-perl';
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = "Perl hooks handler command not found: " + this.handlerCommand + "\nInstall perl hooks handler by running:\n$ cpanm
Dredd::Hooks";
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else if (this.language === 'nodejs') {
    msg = 'Hooks handler should not be used for Node.js. Use Dredd\'s native Node.js hooks instead.';
    return callback(new Error(msg));
  } else if (this.language === 'go') {
    gobin = process.env.GOBIN;
    if (!gobin) {
      gobin = process.env.GOPATH + "/bin";
    }
    this.handlerCommand = gobin + "/goodman";
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = 'Go hooks handler command not found in $GOBIN or $GOPATH/bin\nInstall go hooks handler by running:\n$ go get github.
com/snikch/goodman/cmd/goodman';
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else {
    parsedArgs = spawnArgs(this.language);
    this.handlerCommand = parsedArgs.shift();
    this.handlerCommandArgs = parsedArgs;
    logger.verbose("Using '" + this.handlerCommand + "' as a hook handler command, '" + (this.handlerCommandArgs.join(' ')) + "'
as arguments");
    if (!which.which(this.handlerCommand)) {
      msg = "Hooks handler command not found: " + this.handlerCommand;
      return callback(new Error(msg));
    } else {
      return callback();
    }
  }
}
```
- example usage
```shell
...
  this.clientConnected = false;
  this.connectError = false;
  this.emitter = new EventEmitter;
}

HooksWorkerClient.prototype.start = function(callback) {
  logger.verbose('Looking up hooks handler implementation:', this.language);
  return this.setCommandAndCheckForExecutables((function(_this) {
    return function(executablesError) {
      if (executablesError) {
        return callback(executablesError);
      }
      logger.verbose('Starting hooks handler.');
      return _this.spawnHandler(function(spawnHandlerError) {
        if (spawnHandlerError) {
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.spawnHandler"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>spawnHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.spawnHandler)
- description and source-code
```javascript
spawnHandler = function (callback) {
  var handlerCommandArgs, pathGlobs, ref, ref1, ref2;
  pathGlobs = [].concat((ref = this.runner.hooks) != null ? (ref1 = ref.configuration) != null ? (ref2 = ref1.options) != null ?
ref2.hookfiles : void 0 : void 0 : void 0);
  handlerCommandArgs = this.handlerCommandArgs.concat(pathGlobs);
  logger.info("Spawning '" + this.language + "' hooks handler process.");
  this.handler = spawn(this.handlerCommand, handlerCommandArgs);
  this.handler.stdout.on('data', function(data) {
    return logger.info("Hooks handler stdout:", data.toString());
  });
  this.handler.stderr.on('data', function(data) {
    return logger.info("Hooks handler stderr:", data.toString());
  });
  this.handler.on('signalTerm', function() {
    return logger.verbose('Gracefully terminating the hooks handler process');
  });
  this.handler.on('signalKill', function() {
    return logger.verbose('Killing the hooks handler process');
  });
  this.handler.on('crash', (function(_this) {
    return function(exitStatus, killed) {
      var msg;
      if (killed) {
        msg = "Hooks handler process '" + _this.handlerCommand + " " + (handlerCommandArgs.join(' ')) + "' was killed.";
      } else {
        msg = "Hooks handler process '" + _this.handlerCommand + " " + (handlerCommandArgs.join(' ')) + "' exited with status: " +
exitStatus;
      }
      logger.error(msg);
      return _this.runner.hookHandlerError = new Error(msg);
    };
  })(this));
  this.handler.on('error', (function(_this) {
    return function(err) {
      return _this.runner.hookHandlerError = err;
    };
  })(this));
  return callback();
}
```
- example usage
```shell
...
logger.verbose('Looking up hooks handler implementation:', this.language);
return this.setCommandAndCheckForExecutables((function(_this) {
  return function(executablesError) {
    if (executablesError) {
      return callback(executablesError);
    }
    logger.verbose('Starting hooks handler.');
    return _this.spawnHandler(function(spawnHandlerError) {
      if (spawnHandlerError) {
        return callback(spawnHandlerError);
      }
      logger.verbose('Connecting to hooks handler.');
      return _this.connectToHandler(function(connectHandlerError) {
        if (connectHandlerError) {
          return callback(connectHandlerError);
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.start"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>start (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.start)
- description and source-code
```javascript
start = function (callback) {
  logger.verbose('Looking up hooks handler implementation:', this.language);
  return this.setCommandAndCheckForExecutables((function(_this) {
    return function(executablesError) {
      if (executablesError) {
        return callback(executablesError);
      }
      logger.verbose('Starting hooks handler.');
      return _this.spawnHandler(function(spawnHandlerError) {
        if (spawnHandlerError) {
          return callback(spawnHandlerError);
        }
        logger.verbose('Connecting to hooks handler.');
        return _this.connectToHandler(function(connectHandlerError) {
          if (connectHandlerError) {
            return callback(connectHandlerError);
          }
          logger.verbose('Registering hooks.');
          return _this.registerHooks(function(registerHooksError) {
            if (registerHooksError) {
              return callback(registerHooksError);
            }
            return callback();
          });
        });
      });
    };
  })(this));
}
```
- example usage
```shell
...
    for (k = 0, len2 = files.length; k < len2; k++) {
      file = files[k];
      loadHookFile(file);
    }
    return callback();
  } else {
    hooksWorkerClient = new HooksWorkerClient(runner);
    return hooksWorkerClient.start(callback);
  }
} else {
  logger.info('Loading hook files in sandboxed context:', files);
  return async.eachSeries(files, function(fileName, nextFile) {
    var resolvedPath;
    resolvedPath = path.resolve(customConfigCwd || process.cwd(), fileName);
    return fs.readFile(resolvedPath, 'utf8', function(readingError, data) {
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.stop"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>stop (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.stop)
- description and source-code
```javascript
stop = function (callback) {
  this.disconnectFromHandler();
  return this.terminateHandler(callback);
}
```
- example usage
```shell
...
        }
        for (index = j = 0, len1 = modifications.length; j < len1; index = ++j) {
          modification = modifications[index];
          console.error(index + " " + modification);
        }
        console.error('FOR TESTING ONLY');
      }
      return _this.stop(hookCallback);
    };
  })(this));
  return callback();
};

return HooksWorkerClient;
...
```

#### <a name="apidoc.element.dredd.hooks_worker_client.prototype.terminateHandler"></a>[function <span class="apidocSignatureSpan">dredd.hooks_worker_client.prototype.</span>terminateHandler (callback)](#apidoc.element.dredd.hooks_worker_client.prototype.terminateHandler)
- description and source-code
```javascript
terminateHandler = function (callback) {
  logger.verbose('Terminating hooks handler process, PID', this.handler.pid);
  if (this.handler.terminated) {
    logger.debug('The hooks handler process has already terminated');
    return callback();
  }
  this.handler.terminate({
    force: true,
    timeout: this.termTimeout,
    retryDelay: this.termRetry
  });
  return this.handler.on('close', function() {
    return callback();
  });
}
```
- example usage
```shell
...
      });
    };
  })(this));
};

HooksWorkerClient.prototype.stop = function(callback) {
  this.disconnectFromHandler();
  return this.terminateHandler(callback);
};

HooksWorkerClient.prototype.terminateHandler = function(callback) {
  logger.verbose('Terminating hooks handler process, PID', this.handler.pid);
  if (this.handler.terminated) {
    logger.debug('The hooks handler process has already terminated');
    return callback();
...
```



# <a name="apidoc.module.dredd.interactive_config"></a>[module dredd.interactive_config](#apidoc.module.dredd.interactive_config)

#### <a name="apidoc.element.dredd.interactive_config.processAnswers"></a>[function <span class="apidocSignatureSpan">dredd.interactive_config.</span>processAnswers (config, answers, callback)](#apidoc.element.dredd.interactive_config.processAnswers)
- description and source-code
```javascript
processAnswers = function (config, answers, callback) {
  if (config == null) {
    config = {};
  }
  if (config['_'] == null) {
    config['_'] = [];
  }
  config['_'][0] = answers['blueprint'];
  config['_'][1] = answers['endpoint'];
  config['server'] = answers['server'] || null;
  config['language'] = answers['language'];
  if (answers['apiary'] === true) {
    config['reporter'] = "apiary";
  }
  if (config['custom'] == null) {
    config['custom'] = {};
  }
  if (answers['apiaryApiKey'] != null) {
    config['custom']['apiaryApiKey'] = answers['apiaryApiKey'];
  }
  if (answers['apiaryApiName'] != null) {
    config['custom']['apiaryApiName'] = answers['apiaryApiName'];
  }
  if (answers['circleAdd'] || answers['circleCreate']) {
    interactiveConfig.updateCircle();
  }
  if (answers['travisAdd'] === true) {
    interactiveConfig.updateTravis();
  }
  callback(config);
}
```
- example usage
```shell
...
  interactiveConfig.updateTravis();
}
callback(config);
};

interactiveConfig.run = function(config, callback) {
interactiveConfig.prompt(config, function(answers) {
  return interactiveConfig.processAnswers(config, answers, callback);
});
};

interactiveConfig.updateCircle = function() {
var base, base1, config, file, yamlData;
file = "circle.yml";
if (fs.existsSync(file)) {
...
```

#### <a name="apidoc.element.dredd.interactive_config.prompt"></a>[function <span class="apidocSignatureSpan">dredd.interactive_config.</span>prompt (config, callback)](#apidoc.element.dredd.interactive_config.prompt)
- description and source-code
```javascript
prompt = function (config, callback) {
  var questions, ref, ref1;
  if (config == null) {
    config = {};
  }
  questions = [];
  questions.push({
    type: "input",
    name: "blueprint",
    message: "Location of the API description document",
    "default": config['blueprint'] || "apiary.apib"
  });
  questions.push({
    type: "input",
    name: "server",
    message: "Command to start API backend server e.g. (bundle exec rails server)",
    "default": config['server']
  });
  questions.push({
    type: "input",
    name: "endpoint",
    message: "URL of tested API endpoint",
    "default": config['endpoint'] || "http://127.0.0.1:3000"
  });
  questions.push({
    type: "list",
    name: "language",
    message: "Programming language of hooks",
    "default": "nodejs",
    choices: ["ruby", "python", "nodejs", "php", "perl", "go"]
  });
  questions.push({
    type: "confirm",
    name: "apiary",
    message: "Do you want to use Apiary test inspector?",
    "default": true,
    when: function(answers) {
      return config['reporter'] !== 'apiary';
    }
  });
  questions.push({
    type: "input",
    name: "apiaryApiKey",
    message: "Please enter Apiary API key or leave empty for anonymous reporter",
    "default": (ref = config['custom']) != null ? ref['apiaryApiKey'] : void 0,
    when: function(answers) {
      var ref1;
      return answers['apiary'] === true && (((ref1 = config['custom']) != null ? ref1['apiaryApiKey'] : void 0) == null);
    }
  });
  questions.push({
    type: "input",
    name: "apiaryApiName",
    message: "Please enter Apiary API name",
    "default": (ref1 = config['custom']) != null ? ref1['apiaryApiName'] : void 0,
    when: function(answers) {
      var ref2;
      return (answers['apiary'] === true && (((ref2 = config['custom']) != null ? ref2['apiaryApiName'] : void 0) == null)) && (
answers['apiary'] === true && answers['apiaryApiKey'] !== '');
    }
  });
  questions.push({
    type: "confirm",
    name: "travisAdd",
    message: "Found Travis CI configuration, do you want to add Dredd to the build?",
    "default": true,
    when: function() {
      return fs.existsSync('.travis.yml');
    }
  });
  questions.push({
    type: "confirm",
    name: "circleAdd",
    message: "Found CircleCI configuration, do you want to add Dredd to the build?",
    "default": true,
    when: function() {
      return fs.existsSync('circle.yml');
    }
  });
  questions.push({
    type: "confirm",
    name: "circleCreate",
    message: "Dredd is best served with Continuous Integration. Create CircleCI config for Dredd?",
    when: function(answers) {
      return !fs.existsSync('circle.yml') && !fs.existsSync('.travis.yml');
    }
  });
  return inquirer.prompt(questions).then(callback);
}
```
- example usage
```shell
...
  type: "confirm",
  name: "circleCreate",
  message: "Dredd is best served with Continuous Integration. Create CircleCI config for Dredd?",
  when: function(answers) {
    return !fs.existsSync('circle.yml') && !fs.existsSync('.travis.yml');
  }
});
return inquirer.prompt(questions).then(callback);
};

interactiveConfig.processAnswers = function(config, answers, callback) {
if (config == null) {
  config = {};
}
if (config['_'] == null) {
...
```

#### <a name="apidoc.element.dredd.interactive_config.run"></a>[function <span class="apidocSignatureSpan">dredd.interactive_config.</span>run (config, callback)](#apidoc.element.dredd.interactive_config.run)
- description and source-code
```javascript
run = function (config, callback) {
  interactiveConfig.prompt(config, function(answers) {
    return interactiveConfig.processAnswers(config, answers, callback);
  });
}
```
- example usage
```shell
...
  }
};

DreddCommand.prototype.runExitingActions = function() {
  if (this.argv["_"][0] === "init" || this.argv.init === true) {
    logger.silly('Starting interactive configuration.');
    this.finished = true;
    return interactiveConfig.run(this.argv, (function(_this) {
      return function(config) {
        configUtils.save(config);
        console.log("");
        console.log("Configuration saved to dredd.yml");
        console.log("");
        if (config['language'] === "nodejs") {
          console.log("Run test now, with:");
...
```

#### <a name="apidoc.element.dredd.interactive_config.updateCircle"></a>[function <span class="apidocSignatureSpan">dredd.interactive_config.</span>updateCircle ()](#apidoc.element.dredd.interactive_config.updateCircle)
- description and source-code
```javascript
updateCircle = function () {
  var base, base1, config, file, yamlData;
  file = "circle.yml";
  if (fs.existsSync(file)) {
    config = yaml.safeLoad(fs.readFileSync(file));
  } else {
    config = {};
  }
  if (config['dependencies'] == null) {
    config['dependencies'] = {};
  }
  if ((base = config['dependencies'])['pre'] == null) {
    base['pre'] = [];
  }
  if (config['dependencies']['pre'].indexOf("npm install -g dredd") === -1) {
    config['dependencies']['pre'].push("npm install -g dredd@" + packageData.version);
  }
  if (config['test'] == null) {
    config['test'] = {};
  }
  if ((base1 = config['test'])['pre'] == null) {
    base1['pre'] = [];
  }
  if (config['test']['pre'].indexOf("dredd") === -1) {
    config['test']['pre'].push("dredd");
  }
  yamlData = yaml.safeDump(config);
  fs.writeFileSync(file, yamlData);
}
```
- example usage
```shell
...
  if (answers['apiaryApiKey'] != null) {
    config['custom']['apiaryApiKey'] = answers['apiaryApiKey'];
  }
  if (answers['apiaryApiName'] != null) {
    config['custom']['apiaryApiName'] = answers['apiaryApiName'];
  }
  if (answers['circleAdd'] || answers['circleCreate']) {
    interactiveConfig.updateCircle();
  }
  if (answers['travisAdd'] === true) {
    interactiveConfig.updateTravis();
  }
  callback(config);
};
...
```

#### <a name="apidoc.element.dredd.interactive_config.updateTravis"></a>[function <span class="apidocSignatureSpan">dredd.interactive_config.</span>updateTravis ()](#apidoc.element.dredd.interactive_config.updateTravis)
- description and source-code
```javascript
updateTravis = function () {
  var config, file, yamlData;
  file = ".travis.yml";
  if (fs.existsSync(file)) {
    config = yaml.safeLoad(fs.readFileSync(file));
  } else {
    config = {};
  }
  if (config['before_install'] == null) {
    config['before_install'] = [];
  }
  if (config['before_install'].indexOf("npm install -g dredd") === -1) {
    config['before_install'].push("npm install -g dredd@" + packageData.version);
  }
  if (config['before_script'] == null) {
    config['before_script'] = [];
  }
  if (config['before_script'].indexOf("dredd") === -1) {
    config['before_script'].push("dredd");
  }
  yamlData = yaml.safeDump(config);
  fs.writeFileSync(file, yamlData);
}
```
- example usage
```shell
...
if (answers['apiaryApiName'] != null) {
  config['custom']['apiaryApiName'] = answers['apiaryApiName'];
}
if (answers['circleAdd'] || answers['circleCreate']) {
  interactiveConfig.updateCircle();
}
if (answers['travisAdd'] === true) {
  interactiveConfig.updateTravis();
}
callback(config);
};

interactiveConfig.run = function(config, callback) {
interactiveConfig.prompt(config, function(answers) {
  return interactiveConfig.processAnswers(config, answers, callback);
...
```



# <a name="apidoc.module.dredd.logger"></a>[module dredd.logger](#apidoc.module.dredd.logger)

#### <a name="apidoc.element.dredd.logger.actual"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>actual (msg)](#apidoc.element.dredd.logger.actual)
- description and source-code
```javascript
actual = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.complete"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>complete (msg)](#apidoc.element.dredd.logger.complete)
- description and source-code
```javascript
complete = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.debug"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>debug (msg)](#apidoc.element.dredd.logger.debug)
- description and source-code
```javascript
debug = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...

  DreddCommand.prototype.stopServer = function(callback) {
if (this.serverProcess == null) {
  logger.verbose('No backend server process to terminate.');
  return callback();
}
if (this.serverProcess.terminated) {
  logger.debug('The backend server process has already terminated');
  return callback();
}
logger.verbose('Terminating backend server process, PID', this.serverProcess.pid);
this.serverProcess.terminate({
  force: true
});
return this.serverProcess.on('exit', function() {
...
```

#### <a name="apidoc.element.dredd.logger.error"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>error (msg)](#apidoc.element.dredd.logger.error)
- description and source-code
```javascript
error = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
  }
};

DreddCommand.prototype.checkRequiredArgs = function() {
  var argError;
  argError = false;
  if (this.argv._[0] == null) {
    console.error("\nError: Must specify path to API description document.");
    argError = true;
  }
  if (this.argv._[1] == null) {
    console.error("\nError: Must specify URL of the tested API instance.");
    argError = true;
  }
  if (argError) {
...
```

#### <a name="apidoc.element.dredd.logger.expected"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>expected (msg)](#apidoc.element.dredd.logger.expected)
- description and source-code
```javascript
expected = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.fail"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>fail (msg)](#apidoc.element.dredd.logger.fail)
- description and source-code
```javascript
fail = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.hook"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>hook (msg)](#apidoc.element.dredd.logger.hook)
- description and source-code
```javascript
hook = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.info"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>info (msg)](#apidoc.element.dredd.logger.info)
- description and source-code
```javascript
info = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
runner.hooks.configuration = clone(runner != null ? runner.configuration : void 0);
files = [];
globs = [].concat(runner != null ? (ref4 = runner.configuration) != null ? (ref5 = ref4.options) != null ? ref5.hookfiles : void
 0 : void 0 : void 0);
for (j = 0, len1 = globs.length; j < len1; j++) {
  globItem = globs[j];
  files = files.concat(glob.sync(globItem));
}
logger.info('Found Hookfiles:', files);
if (!runner.configuration.options.sandbox === true) {
  if ((runner != null ? (ref6 = runner.configuration) != null ? (ref7 = ref6.options) != null ? ref7.language : void 0 : void 0 :
void 0) === "" || (runner != null ? (ref8 = runner.configuration) != null ? (ref9 = ref8.options) != null ? ref9.language : void
 0 : void 0 : void 0) === void 0 || (runner != null ? (ref10 = runner.configuration) != null ? (ref11 = ref10.options) != null ?
ref11.language : void 0 : void 0 : void 0) === "nodejs") {
    for (k = 0, len2 = files.length; k < len2; k++) {
      file = files[k];
      loadHookFile(file);
    }
    return callback();
...
```

#### <a name="apidoc.element.dredd.logger.pass"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>pass (msg)](#apidoc.element.dredd.logger.pass)
- description and source-code
```javascript
pass = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.request"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>request (msg)](#apidoc.element.dredd.logger.request)
- description and source-code
```javascript
request = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.silly"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>silly (msg)](#apidoc.element.dredd.logger.silly)
- description and source-code
```javascript
silly = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
    this.optimist.showHelp(console.error);
    return this._processExit(1);
  }
};

DreddCommand.prototype.runExitingActions = function() {
  if (this.argv["_"][0] === "init" || this.argv.init === true) {
    logger.silly('Starting interactive configuration.');
    this.finished = true;
    return interactiveConfig.run(this.argv, (function(_this) {
      return function(config) {
        configUtils.save(config);
        console.log("");
        console.log("Configuration saved to dredd.yml");
        console.log("");
...
```

#### <a name="apidoc.element.dredd.logger.skip"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>skip (msg)](#apidoc.element.dredd.logger.skip)
- description and source-code
```javascript
skip = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.test"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>test (msg)](#apidoc.element.dredd.logger.test)
- description and source-code
```javascript
test = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.logger.verbose"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>verbose (msg)](#apidoc.element.dredd.logger.verbose)
- description and source-code
```javascript
verbose = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
};

configureReporters = function(config, stats, tests, runner) {
var addCli, addReporter, baseReporter, i, j, len, outputs, path, reporter, reporters, results, usedFileReporters, usedFileReportersLength
;
baseReporter = new BaseReporter(config.emitter, stats, tests);
reporters = config.options.reporter;
outputs = config.options.output;
logger.verbose('Configuring reporters:', reporters, outputs);
addCli = function(reporters) {
  var cliReporter, usedCliReporters;
  if (reporters.length > 0) {
    usedCliReporters = intersection(reporters, cliReporters);
    if (usedCliReporters.length === 0) {
      return cliReporter = new CliReporter(config.emitter, stats, tests, config.options['inline-errors'], config.options.details
);
    } else {
...
```

#### <a name="apidoc.element.dredd.logger.warn"></a>[function <span class="apidocSignatureSpan">dredd.logger.</span>warn (msg)](#apidoc.element.dredd.logger.warn)
- description and source-code
```javascript
warn = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
  try {
    proxyquire(filePath, {
      'hooks': runner.hooks
    });
    return fixLegacyTransactionNames(runner.hooks);
  } catch (error1) {
    error = error1;
    return logger.warn("Skipping hook loading. Error reading hook file '" + filePath + "'. This probably means one or more of your
 hook files are invalid.\nMessage: " + error.message + "\nStack: " + error.stack);
  }
};
loadSandboxHooksFromStrings = function(callback) {
  if (typeof runner.configuration.hooksData !== 'object' || Array.isArray(runner.configuration.hooksData) !== false) {
    return callback(new Error("hooksData option must be an object e.g. {'filename.js':'console.log(\"Hey!\")'}"));
  }
  return async.eachSeries(Object.keys(runner.configuration.hooksData), function(key, nextHook) {
...
```



# <a name="apidoc.module.dredd.transaction_runner"></a>[module dredd.transaction_runner](#apidoc.module.dredd.transaction_runner)

#### <a name="apidoc.element.dredd.transaction_runner.transaction_runner"></a>[function <span class="apidocSignatureSpan">dredd.</span>transaction_runner (configuration1)](#apidoc.element.dredd.transaction_runner.transaction_runner)
- description and source-code
```javascript
function TransactionRunner(configuration1) {
  this.configuration = configuration1;
  this.executeTransaction = bind(this.executeTransaction, this);
  this.configureTransaction = bind(this.configureTransaction, this);
  this.logs = [];
  this.hookStash = {};
  this.error = null;
  this.hookHandlerError = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.dredd.transaction_runner.prototype"></a>[module dredd.transaction_runner.prototype](#apidoc.module.dredd.transaction_runner.prototype)

#### <a name="apidoc.element.dredd.transaction_runner.prototype.config"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>config (config)](#apidoc.element.dredd.transaction_runner.prototype.config)
- description and source-code
```javascript
config = function (config) {
  this.configuration = config;
  return this.multiBlueprint = Object.keys(this.configuration.data).length > 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.configureTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>configureTransaction (transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.configureTransaction)
- description and source-code
```javascript
configureTransaction = function (transaction, callback) {
  var configuration, configuredTransaction, expected, flatHeaders, fullPath, header, headerKey, headerValue, i, len, mediaType,
origin, ref, ref1, request, response, skip, splitIndex, status, system;
  configuration = this.configuration;
  origin = transaction.origin, request = transaction.request, response = transaction.response;
  mediaType = ((ref = configuration.data[origin.filename]) != null ? ref.mediaType : void 0) || 'text/vnd.apiblueprint';
  if (this.parsedUrl == null) {
    this.parsedUrl = this.parseServerUrl(configuration.server);
  }
  fullPath = this.getFullPath(this.parsedUrl.path, request.uri);
  flatHeaders = flattenHeaders(request['headers']);
  if (!flatHeaders['User-Agent']) {
    system = os.type() + ' ' + os.release() + '; ' + os.arch();
    flatHeaders['User-Agent'] = "Dredd/" + packageData.version + " (" + system + ")";
  }
  if (configuration.options.header.length > 0) {
    ref1 = configuration.options.header;
    for (i = 0, len = ref1.length; i < len; i++) {
      header = ref1[i];
      splitIndex = header.indexOf(':');
      headerKey = header.substring(0, splitIndex);
      headerValue = header.substring(splitIndex + 1);
      flatHeaders[headerKey] = headerValue;
    }
  }
  request['headers'] = flatHeaders;
  expected = {
    headers: flattenHeaders(response['headers']),
    body: response['body'],
    statusCode: response['status']
  };
  if (response['schema']) {
    expected['bodySchema'] = response['schema'];
  }
  if (!this.multiBlueprint) {
    transaction.name = transaction.name.replace(transaction.origin.apiName + " > ", "");
  }
  skip = false;
  if (mediaType.indexOf('swagger') !== -1) {
    status = parseInt(response.status, 10);
    if (status < 200 || status >= 300) {
      skip = true;
    }
  }
  configuredTransaction = {
    name: transaction.name,
    id: request.method + ' ' + request.uri,
    host: this.parsedUrl.hostname,
    port: this.parsedUrl.port,
    request: request,
    expected: expected,
    origin: origin,
    fullPath: fullPath,
    protocol: this.parsedUrl.protocol,
    skip: skip
  };
  return callback(null, configuredTransaction);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.createTest"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>createTest (transaction)](#apidoc.element.dredd.transaction_runner.prototype.createTest)
- description and source-code
```javascript
createTest = function (transaction) {
  return {
    status: '',
    title: transaction.id,
    message: transaction.name,
    origin: transaction.origin,
    startedAt: transaction.startedAt
  };
}
```
- example usage
```shell
...
};

TransactionRunner.prototype.emitHookError = function(error, data) {
  var test;
  if (!(error instanceof Error)) {
    error = new Error(error);
  }
  test = this.createTest(data);
  test.request = data.request;
  return this.emitError(error, test);
};

TransactionRunner.prototype.sandboxedHookResultsHandler = function(err, data, results, callback) {
  var i, key, len, log, ref, ref1, value;
  if (results == null) {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.emitError"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitError (error, test)](#apidoc.element.dredd.transaction_runner.prototype.emitError)
- description and source-code
```javascript
emitError = function (error, test) {
  logger.debug('Emitting to reporters: test error');
  this.configuration.emitter.emit('test error', error, test, function() {});
  return this.error = this.error || error;
}
```
- example usage
```shell
...
TransactionRunner.prototype.emitHookError = function(error, data) {
  var test;
  if (!(error instanceof Error)) {
    error = new Error(error);
  }
  test = this.createTest(data);
  test.request = data.request;
  return this.emitError(error, test);
};

TransactionRunner.prototype.sandboxedHookResultsHandler = function(err, data, results, callback) {
  var i, key, len, log, ref, ref1, value;
  if (results == null) {
    results = {};
  }
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.emitHookError"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitHookError (error, data)](#apidoc.element.dredd.transaction_runner.prototype.emitHookError)
- description and source-code
```javascript
emitHookError = function (error, data) {
  var test;
  if (!(error instanceof Error)) {
    error = new Error(error);
  }
  test = this.createTest(data);
  test.request = data.request;
  return this.emitError(error, test);
}
```
- example usage
```shell
...
var error, hookFn, i, len, transaction, transactions;
hookFn = hooks[hookFnIndex];
try {
  if (legacy) {
    return _this.runLegacyHook(hookFn, data, function(err) {
      if (err) {
        logger.debug('Legacy hook errored:', err);
        _this.emitHookError(err, data);
      }
      return runHookCallback();
    });
  } else {
    return _this.runHook(hookFn, data, function(err) {
      if (err) {
        logger.debug('Hook errored:', err);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.emitResult"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>emitResult (transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.emitResult)
- description and source-code
```javascript
emitResult = function (transaction, callback) {
  if (this.error || !transaction.test) {
    logger.debug('No emission of test data to reporters', this.error, transaction.test);
    this.error = null;
    return callback();
  }
  if (transaction.skip) {
    logger.debug('Emitting to reporters: test skip');
    this.configuration.emitter.emit('test skip', transaction.test, function() {});
    return callback();
  }
  if (transaction.test.valid) {
    if (transaction.fail) {
      this.failTransaction(transaction, "Failed in after hook: " + transaction.fail);
      logger.debug('Emitting to reporters: test fail');
      this.configuration.emitter.emit('test fail', transaction.test, function() {});
    } else {
      logger.debug('Emitting to reporters: test pass');
      this.configuration.emitter.emit('test pass', transaction.test, function() {});
    }
    return callback();
  }
  logger.debug('Emitting to reporters: test fail');
  this.configuration.emitter.emit('test fail', transaction.test, function() {});
  return callback();
}
```
- example usage
```shell
...
          }
          logger.verbose('Running \'after\' hooks');
          return _this.runHooksForData(hooks.afterHooks[transaction.name], transaction, false, function() {
            if (_this.hookHandlerError) {
              return iterationCallback(_this.hookHandlerError);
            }
            logger.debug("Evaluating results of transaction execution #" + (transactionIndex + 1) + ":", transaction.name);
            return _this.emitResult(transaction, iterationCallback);
          });
        });
      });
    });
  });
}, function(iterationError) {
  if (iterationError) {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.ensureTransactionResultsGeneralSection"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>ensureTransactionResultsGeneralSection (transaction)](#apidoc.element.dredd.transaction_runner.prototype.ensureTransactionResultsGeneralSection)
- description and source-code
```javascript
ensureTransactionResultsGeneralSection = function (transaction) {
  var base, base1;
  if (transaction.results == null) {
    transaction.results = {};
  }
  if ((base = transaction.results).general == null) {
    base.general = {};
  }
  return (base1 = transaction.results.general).results != null ? base1.results : base1.results = [];
}
```
- example usage
```shell
...
    startedAt: transaction.startedAt
  };
};

TransactionRunner.prototype.failTransaction = function(transaction, reason) {
  var base;
  transaction.fail = true;
  this.ensureTransactionResultsGeneralSection(transaction);
  if (reason) {
    transaction.results.general.results.push({
      severity: 'error',
      message: reason
    });
  }
  if (transaction.test == null) {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.executeAllTransactions"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>executeAllTransactions (transactions, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.executeAllTransactions)
- description and source-code
```javascript
executeAllTransactions = function (transactions, hooks, callback) {
  var i, len, transaction;
  if (!hooks.transactions) {
    hooks.transactions = {};
    for (i = 0, len = transactions.length; i < len; i++) {
      transaction = transactions[i];
      hooks.transactions[transaction.name] = transaction;
    }
  }
  if (this.hookHandlerError) {
    return callback(this.hookHandlerError);
  }
  logger.verbose('Running \'beforeAll\' hooks');
  return this.runHooksForData(hooks.beforeAllHooks, transactions, true, (function(_this) {
    return function() {
      if (_this.hookHandlerError) {
        return callback(_this.hookHandlerError);
      }
      return async.timesSeries(transactions.length, function(transactionIndex, iterationCallback) {
        transaction = transactions[transactionIndex];
        logger.verbose("Processing transaction #" + (transactionIndex + 1) + ":", transaction.name);
        logger.verbose('Running \'beforeEach\' hooks');
        return _this.runHooksForData(hooks.beforeEachHooks, transaction, false, function() {
          if (_this.hookHandlerError) {
            return iterationCallback(_this.hookHandlerError);
          }
          logger.verbose('Running \'before\' hooks');
          return _this.runHooksForData(hooks.beforeHooks[transaction.name], transaction, false, function() {
            if (_this.hookHandlerError) {
              return iterationCallback(_this.hookHandlerError);
            }
            return _this.executeTransaction(transaction, hooks, function() {
              if (_this.hookHandlerError) {
                return iterationCallback(_this.hookHandlerError);
              }
              logger.verbose('Running \'afterEach\' hooks');
              return _this.runHooksForData(hooks.afterEachHooks, transaction, false, function() {
                if (_this.hookHandlerError) {
                  return iterationCallback(_this.hookHandlerError);
                }
                logger.verbose('Running \'after\' hooks');
                return _this.runHooksForData(hooks.afterHooks[transaction.name], transaction, false, function() {
                  if (_this.hookHandlerError) {
                    return iterationCallback(_this.hookHandlerError);
                  }
                  logger.debug("Evaluating results of transaction execution #" + (transactionIndex + 1) + ":", transaction.name);
                  return _this.emitResult(transaction, iterationCallback);
                });
              });
            });
          });
        });
      }, function(iterationError) {
        if (iterationError) {
          return callback(iterationError);
        }
        logger.verbose('Running \'afterAll\' hooks');
        return _this.runHooksForData(hooks.afterAllHooks, transactions, true, function() {
          if (_this.hookHandlerError) {
            return callback(_this.hookHandlerError);
          }
          return callback();
        });
      });
    };
  })(this));
}
```
- example usage
```shell
...
      transactions = results;
      logger.verbose('Reading hook files and registering hooks');
      return addHooks(_this, transactions, function(addHooksError) {
        if (addHooksError) {
          return callback(addHooksError);
        }
        logger.verbose('Executing HTTP transactions');
        return _this.executeAllTransactions(transactions, _this.hooks, callback);
      });
    };
  })(this));
};

TransactionRunner.prototype.executeAllTransactions = function(transactions, hooks, callback) {
  var i, len, transaction;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.executeTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>executeTransaction (transaction, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.executeTransaction)
- description and source-code
```javascript
executeTransaction = function (transaction, hooks, callback) {
  var m, ref, ref1, ref2, test;
  if (!callback) {
    ref = [hooks, void 0], callback = ref[0], hooks = ref[1];
  }
  transaction.startedAt = Date.now();
  test = this.createTest(transaction);
  logger.debug('Emitting to reporters: test start');
  this.configuration.emitter.emit('test start', test, function() {});
  this.ensureTransactionResultsGeneralSection(transaction);
  if (transaction.skip) {
    logger.verbose('HTTP transaction was marked in hooks as to be skipped. Skipping');
    transaction.test = test;
    this.skipTransaction(transaction, 'Skipped in before hook');
    return callback();
  } else if (transaction.fail) {
    logger.verbose('HTTP transaction was marked in hooks as to be failed. Reporting as failed');
    transaction.test = test;
    this.failTransaction(transaction, "Failed in before hook: " + transaction.fail);
    return callback();
  } else if (this.configuration.options['dry-run']) {
    logger.info('Dry run. Not performing HTTP request');
    transaction.test = test;
    this.skipTransaction(transaction);
    return callback();
  } else if (this.configuration.options.names) {
    logger.info(transaction.name);
    transaction.test = test;
    this.skipTransaction(transaction);
    return callback();
  } else if (this.configuration.options.method.length > 0 && !(ref1 = transaction.request.method, indexOf.call(this.configuration
.options.method, ref1) >= 0)) {
    logger.info("Only " + (((function() {
      var i, len, ref2, results1;
      ref2 = this.configuration.options.method;
      results1 = [];
      for (i = 0, len = ref2.length; i < len; i++) {
        m = ref2[i];
        results1.push(m.toUpperCase());
      }
      return results1;
    }).call(this)).join(', ')) + "requests are set to be executed. Not performing HTTP " + (transaction.request.method.toUpperCase
()) + " request.");
    transaction.test = test;
    this.skipTransaction(transaction);
    return callback();
  } else if (this.configuration.options.only.length > 0 && !(ref2 = transaction.name, indexOf.call(this.configuration.options.only
, ref2) >= 0)) {
    logger.info("Only '" + this.configuration.options.only + "' transaction is set to be executed. Not performing HTTP request for
 '" + transaction.name + "'.");
    transaction.test = test;
    this.skipTransaction(transaction);
    return callback();
  } else {
    return this.performRequestAndValidate(test, transaction, hooks, callback);
  }
}
```
- example usage
```shell
...
  return iterationCallback(_this.hookHandlerError);
}
logger.verbose('Running \'before\' hooks');
return _this.runHooksForData(hooks.beforeHooks[transaction.name], transaction, false, function() {
  if (_this.hookHandlerError) {
    return iterationCallback(_this.hookHandlerError);
  }
  return _this.executeTransaction(transaction, hooks, function() {
    if (_this.hookHandlerError) {
      return iterationCallback(_this.hookHandlerError);
    }
    logger.verbose('Running \'afterEach\' hooks');
    return _this.runHooksForData(hooks.afterEachHooks, transaction, false, function() {
      if (_this.hookHandlerError) {
        return iterationCallback(_this.hookHandlerError);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.failTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>failTransaction (transaction, reason)](#apidoc.element.dredd.transaction_runner.prototype.failTransaction)
- description and source-code
```javascript
failTransaction = function (transaction, reason) {
  var base;
  transaction.fail = true;
  this.ensureTransactionResultsGeneralSection(transaction);
  if (reason) {
    transaction.results.general.results.push({
      severity: 'error',
      message: reason
    });
  }
  if (transaction.test == null) {
    transaction.test = this.createTest(transaction);
  }
  transaction.test.status = 'fail';
  if (reason) {
    transaction.test.message = reason;
  }
  return (base = transaction.test).results != null ? base.results : base.results = transaction.results;
}
```
- example usage
```shell
...
  }
} catch (error1) {
  error = error1;
  if (error instanceof chai.AssertionError) {
    transactions = Array.isArray(data) ? data : [data];
    for (i = 0, len = transactions.length; i < len; i++) {
      transaction = transactions[i];
      _this.failTransaction(transaction, "Failed assertion in hooks: " + error.message);
    }
  } else {
    logger.debug('Hook errored:', error);
    _this.emitHookError(error, data);
  }
  return runHookCallback();
}
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.getFullPath"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>getFullPath (serverPath, requestPath)](#apidoc.element.dredd.transaction_runner.prototype.getFullPath)
- description and source-code
```javascript
getFullPath = function (serverPath, requestPath) {
  var segment, segments, trailingSlash;
  if (serverPath === '/') {
    return requestPath;
  }
  if (!requestPath) {
    return serverPath;
  }
  segments = [serverPath, requestPath];
  segments = (function() {
    var i, len, results1;
    results1 = [];
    for (i = 0, len = segments.length; i < len; i++) {
      segment = segments[i];
      results1.push(segment.replace(/^\/|\/$/g, ''));
    }
    return results1;
  })();
  trailingSlash = requestPath !== '/' && requestPath.slice(-1) === '/' ? '/' : '';
  return '/' + segments.join('/') + trailingSlash;
}
```
- example usage
```shell
...
var configuration, configuredTransaction, expected, flatHeaders, fullPath, header, headerKey, headerValue, i, len, mediaType, origin
, ref, ref1, request, response, skip, splitIndex, status, system;
configuration = this.configuration;
origin = transaction.origin, request = transaction.request, response = transaction.response;
mediaType = ((ref = configuration.data[origin.filename]) != null ? ref.mediaType : void 0) || 'text/vnd.apiblueprint';
if (this.parsedUrl == null) {
  this.parsedUrl = this.parseServerUrl(configuration.server);
}
fullPath = this.getFullPath(this.parsedUrl.path, request.uri);
flatHeaders = flattenHeaders(request['headers']);
if (!flatHeaders['User-Agent']) {
  system = os.type() + ' ' + os.release() + '; ' + os.arch();
  flatHeaders['User-Agent'] = "Dredd/" + packageData.version + " (" + system + ")";
}
if (configuration.options.header.length > 0) {
  ref1 = configuration.options.header;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.getRequestOptionsFromTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>getRequestOptionsFromTransaction (transaction)](#apidoc.element.dredd.transaction_runner.prototype.getRequestOptionsFromTransaction)
- description and source-code
```javascript
getRequestOptionsFromTransaction = function (transaction) {
  var options, urlObject;
  urlObject = {
    protocol: transaction.protocol,
    hostname: transaction.host,
    port: transaction.port
  };
  options = clone(this.configuration.http || {});
  options.uri = url.format(urlObject) + transaction.fullPath;
  options.method = transaction.request.method;
  options.headers = transaction.request.headers;
  options.body = transaction.request.body;
  options.proxy = false;
  return options;
}
```
- example usage
```shell
...
    return headers['Content-Length'] = body ? Buffer.byteLength(body) : 0;
  }
};

TransactionRunner.prototype.performRequestAndValidate = function(test, transaction, hooks, callback) {
  var error, handleRequest, requestOptions;
  this.setContentLength(transaction);
  requestOptions = this.getRequestOptionsFromTransaction(transaction);
  handleRequest = (function(_this) {
    return function(err, res, body) {
      var real;
      if (err) {
        logger.debug('Requesting tested server errored:', ("" + err) || err.code);
        test.title = transaction.id;
        test.expected = transaction.expected;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.isMultipart"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>isMultipart (requestOptions)](#apidoc.element.dredd.transaction_runner.prototype.isMultipart)
- description and source-code
```javascript
isMultipart = function (requestOptions) {
  var caseInsensitiveRequestHeaders, key, ref, ref1, value;
  caseInsensitiveRequestHeaders = {};
  ref = requestOptions.headers;
  for (key in ref) {
    value = ref[key];
    caseInsensitiveRequestHeaders[key.toLowerCase()] = value;
  }
  return ((ref1 = caseInsensitiveRequestHeaders['content-type']) != null ? ref1.indexOf("multipart") : void 0) > -1;
}
```
- example usage
```shell
...
          return callback(_this.hookHandlerError);
        }
        return _this.validateTransaction(test, transaction, callback);
      });
    });
  };
})(this);
if (transaction.request['body'] && this.isMultipart(requestOptions)) {
  this.replaceLineFeedInBody(transaction, requestOptions);
}
try {
  return this.performRequest(requestOptions, handleRequest);
} catch (error1) {
  error = error1;
  logger.debug('Requesting tested server errored:', error);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.parseServerUrl"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>parseServerUrl (serverUrl)](#apidoc.element.dredd.transaction_runner.prototype.parseServerUrl)
- description and source-code
```javascript
parseServerUrl = function (serverUrl) {
  if (!serverUrl.match(/^https?:\/\//i)) {
    serverUrl = 'http://' + serverUrl.replace(/^[:\/]*/, '');
  }
  return url.parse(serverUrl);
}
```
- example usage
```shell
...

  TransactionRunner.prototype.configureTransaction = function(transaction, callback) {
var configuration, configuredTransaction, expected, flatHeaders, fullPath, header, headerKey, headerValue, i, len, mediaType, origin
, ref, ref1, request, response, skip, splitIndex, status, system;
configuration = this.configuration;
origin = transaction.origin, request = transaction.request, response = transaction.response;
mediaType = ((ref = configuration.data[origin.filename]) != null ? ref.mediaType : void 0) || 'text/vnd.apiblueprint';
if (this.parsedUrl == null) {
  this.parsedUrl = this.parseServerUrl(configuration.server);
}
fullPath = this.getFullPath(this.parsedUrl.path, request.uri);
flatHeaders = flattenHeaders(request['headers']);
if (!flatHeaders['User-Agent']) {
  system = os.type() + ' ' + os.release() + '; ' + os.arch();
  flatHeaders['User-Agent'] = "Dredd/" + packageData.version + " (" + system + ")";
}
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.performRequest"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>performRequest (options, callback)](#apidoc.element.dredd.transaction_runner.prototype.performRequest)
- description and source-code
```javascript
performRequest = function (options, callback) {
  var protocol;
  protocol = options.uri.split(':')[0].toUpperCase();
  logger.verbose("About to perform an " + protocol + " request to the server under test: " + options.method + " " + options.uri);
  return requestLib(options, callback);
}
```
- example usage
```shell
...
    });
  };
})(this);
if (transaction.request['body'] && this.isMultipart(requestOptions)) {
  this.replaceLineFeedInBody(transaction, requestOptions);
}
try {
  return this.performRequest(requestOptions, handleRequest);
} catch (error1) {
  error = error1;
  logger.debug('Requesting tested server errored:', error);
  test.title = transaction.id;
  test.expected = transaction.expected;
  test.request = transaction.request;
  this.emitError(error, test);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.performRequestAndValidate"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>performRequestAndValidate (test, transaction, hooks, callback)](#apidoc.element.dredd.transaction_runner.prototype.performRequestAndValidate)
- description and source-code
```javascript
performRequestAndValidate = function (test, transaction, hooks, callback) {
  var error, handleRequest, requestOptions;
  this.setContentLength(transaction);
  requestOptions = this.getRequestOptionsFromTransaction(transaction);
  handleRequest = (function(_this) {
    return function(err, res, body) {
      var real;
      if (err) {
        logger.debug('Requesting tested server errored:', ("" + err) || err.code);
        test.title = transaction.id;
        test.expected = transaction.expected;
        test.request = transaction.request;
        _this.emitError(err, test);
        return callback();
      }
      logger.verbose('Handling HTTP response from tested server');
      real = {
        statusCode: res.statusCode,
        headers: res.headers,
        body: body
      };
      transaction['real'] = real;
      logger.verbose('Running \'beforeEachValidation\' hooks');
      return _this.runHooksForData(hooks != null ? hooks.beforeEachValidationHooks : void 0, transaction, false, function() {
        if (_this.hookHandlerError) {
          return callback(_this.hookHandlerError);
        }
        logger.verbose('Running \'beforeValidation\' hooks');
        return _this.runHooksForData(hooks != null ? hooks.beforeValidationHooks[transaction.name] : void 0, transaction, false,
function() {
          if (_this.hookHandlerError) {
            return callback(_this.hookHandlerError);
          }
          return _this.validateTransaction(test, transaction, callback);
        });
      });
    };
  })(this);
  if (transaction.request['body'] && this.isMultipart(requestOptions)) {
    this.replaceLineFeedInBody(transaction, requestOptions);
  }
  try {
    return this.performRequest(requestOptions, handleRequest);
  } catch (error1) {
    error = error1;
    logger.debug('Requesting tested server errored:', error);
    test.title = transaction.id;
    test.expected = transaction.expected;
    test.request = transaction.request;
    this.emitError(error, test);
    return callback();
  }
}
```
- example usage
```shell
...
    return callback();
  } else if (this.configuration.options.only.length > 0 && !(ref2 = transaction.name, indexOf.call(this.configuration.options.only
, ref2) >= 0)) {
    logger.info("Only '" + this.configuration.options.only + "' transaction is set to be executed. Not performing HTTP request for
 '" + transaction.name + "'.");
    transaction.test = test;
    this.skipTransaction(transaction);
    return callback();
  } else {
    return this.performRequestAndValidate(test, transaction, hooks, callback);
  }
};

TransactionRunner.prototype.setContentLength = function(transaction) {
  var body, calculatedContentLengthValue, contentLengthHeaderName, contentLengthValue, headers;
  headers = transaction.request.headers;
  body = transaction.request.body;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.replaceLineFeedInBody"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>replaceLineFeedInBody (transaction, requestOptions)](#apidoc.element.dredd.transaction_runner.prototype.replaceLineFeedInBody)
- description and source-code
```javascript
replaceLineFeedInBody = function (transaction, requestOptions) {
  if (transaction.request['body'].indexOf('\r\n') === -1) {
    transaction.request['body'] = transaction.request['body'].replace(/\n/g, '\r\n');
    transaction.request['headers']['Content-Length'] = Buffer.byteLength(transaction.request['body'], 'utf8');
    return requestOptions.headers = transaction.request['headers'];
  }
}
```
- example usage
```shell
...
        }
        return _this.validateTransaction(test, transaction, callback);
      });
    });
  };
})(this);
if (transaction.request['body'] && this.isMultipart(requestOptions)) {
  this.replaceLineFeedInBody(transaction, requestOptions);
}
try {
  return this.performRequest(requestOptions, handleRequest);
} catch (error1) {
  error = error1;
  logger.debug('Requesting tested server errored:', error);
  test.title = transaction.id;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.run"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>run (transactions, callback)](#apidoc.element.dredd.transaction_runner.prototype.run)
- description and source-code
```javascript
run = function (transactions, callback) {
  logger.verbose('Sorting HTTP transactions');
  transactions = this.configuration.options['sorted'] ? sortTransactions(transactions) : transactions;
  logger.verbose('Configuring HTTP transactions');
  return async.mapSeries(transactions, this.configureTransaction.bind(this), (function(_this) {
    return function(err, results) {
      transactions = results;
      logger.verbose('Reading hook files and registering hooks');
      return addHooks(_this, transactions, function(addHooksError) {
        if (addHooksError) {
          return callback(addHooksError);
        }
        logger.verbose('Executing HTTP transactions');
        return _this.executeAllTransactions(transactions, _this.hooks, callback);
      });
    };
  })(this));
}
```
- example usage
```shell
...
  }
};

DreddCommand.prototype.runExitingActions = function() {
  if (this.argv["_"][0] === "init" || this.argv.init === true) {
    logger.silly('Starting interactive configuration.');
    this.finished = true;
    return interactiveConfig.run(this.argv, (function(_this) {
      return function(config) {
        configUtils.save(config);
        console.log("");
        console.log("Configuration saved to dredd.yml");
        console.log("");
        if (config['language'] === "nodejs") {
          console.log("Run test now, with:");
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.runHook"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runHook (hook, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runHook)
- description and source-code
```javascript
runHook = function (hook, data, callback) {
  if (typeof hook === 'function') {
    if (hook.length === 1) {
      hook(data);
      callback();
    } else if (hook.length === 2) {
      hook(data, function() {
        return callback();
      });
    }
  }
  if (typeof hook === 'string') {
    return this.runSandboxedHookFromString(hook, data, callback);
  }
}
```
- example usage
```shell
...
    if (err) {
      logger.debug('Legacy hook errored:', err);
      _this.emitHookError(err, data);
    }
    return runHookCallback();
  });
} else {
  return _this.runHook(hookFn, data, function(err) {
    if (err) {
      logger.debug('Hook errored:', err);
      _this.emitHookError(err, data);
    }
    return runHookCallback();
  });
}
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.runHooksForData"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runHooksForData (hooks, data, legacy, callback)](#apidoc.element.dredd.transaction_runner.prototype.runHooksForData)
- description and source-code
```javascript
runHooksForData = function (hooks, data, legacy, callback) {
  var runHookWithData;
  if (legacy == null) {
    legacy = false;
  }
  if ((hooks != null) && Array.isArray(hooks)) {
    logger.debug('Running hooks...');
    runHookWithData = (function(_this) {
      return function(hookFnIndex, runHookCallback) {
        var error, hookFn, i, len, transaction, transactions;
        hookFn = hooks[hookFnIndex];
        try {
          if (legacy) {
            return _this.runLegacyHook(hookFn, data, function(err) {
              if (err) {
                logger.debug('Legacy hook errored:', err);
                _this.emitHookError(err, data);
              }
              return runHookCallback();
            });
          } else {
            return _this.runHook(hookFn, data, function(err) {
              if (err) {
                logger.debug('Hook errored:', err);
                _this.emitHookError(err, data);
              }
              return runHookCallback();
            });
          }
        } catch (error1) {
          error = error1;
          if (error instanceof chai.AssertionError) {
            transactions = Array.isArray(data) ? data : [data];
            for (i = 0, len = transactions.length; i < len; i++) {
              transaction = transactions[i];
              _this.failTransaction(transaction, "Failed assertion in hooks: " + error.message);
            }
          } else {
            logger.debug('Hook errored:', error);
            _this.emitHookError(error, data);
          }
          return runHookCallback();
        }
      };
    })(this);
    return async.timesSeries(hooks.length, runHookWithData, function() {
      return callback();
    });
  } else {
    return callback();
  }
}
```
- example usage
```shell
...
    hooks.transactions[transaction.name] = transaction;
  }
}
if (this.hookHandlerError) {
  return callback(this.hookHandlerError);
}
logger.verbose('Running \'beforeAll\' hooks');
return this.runHooksForData(hooks.beforeAllHooks, transactions, true, (function(_this) {
  return function() {
    if (_this.hookHandlerError) {
      return callback(_this.hookHandlerError);
    }
    return async.timesSeries(transactions.length, function(transactionIndex, iterationCallback) {
      transaction = transactions[transactionIndex];
      logger.verbose("Processing transaction #" + (transactionIndex + 1) + ":", transaction.name);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.runLegacyHook"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runLegacyHook (hook, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runLegacyHook)
- description and source-code
```javascript
runLegacyHook = function (hook, data, callback) {
  if (typeof hook === 'function') {
    if (hook.length === 1) {
      logger.warn('DEPRECATION WARNING!\n\nYou are using only one argument for the 'beforeAll' or 'afterAll' hook function.\nOne
 argument hook functions will be treated as synchronous in the near future.\nTo keep the async behaviour, just define hook function with two parameters.\n\nInterface of the hooks functions will be unified soon across all hook functions:\n\n - 'beforeAll' and 'afterAll' hooks will support sync API depending on number of arguments\n - Signatures of callbacks of all hooks will be the same\n - First passed argument will be a 'transactions' object\n - Second passed argument will be a optional callback function for async\n - 'transactions' object in 'hooks' module object will be removed\n - Manipulation with transaction data will have to be performed on the first function argument');
      hook(callback);
    } else if (hook.length === 2) {
      hook(data, function() {
        return callback();
      });
    }
  }
  if (typeof hook === 'string') {
    return this.runSandboxedHookFromString(hook, data, callback);
  }
}
```
- example usage
```shell
...
logger.debug('Running hooks...');
runHookWithData = (function(_this) {
  return function(hookFnIndex, runHookCallback) {
    var error, hookFn, i, len, transaction, transactions;
    hookFn = hooks[hookFnIndex];
    try {
      if (legacy) {
        return _this.runLegacyHook(hookFn, data, function(err) {
          if (err) {
            logger.debug('Legacy hook errored:', err);
            _this.emitHookError(err, data);
          }
          return runHookCallback();
        });
      } else {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.runSandboxedHookFromString"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>runSandboxedHookFromString (hookString, data, callback)](#apidoc.element.dredd.transaction_runner.prototype.runSandboxedHookFromString)
- description and source-code
```javascript
runSandboxedHookFromString = function (hookString, data, callback) {
  var sandbox, wrappedCode;
  wrappedCode = this.sandboxedWrappedCode(hookString);
  sandbox = new Pitboss(wrappedCode, {
    timeout: 500
  });
  return sandbox.run({
    context: {
      '_data': data,
      '_logs': [],
      'stash': this.hookStash
    },
    libraries: {
      '_log': sandboxedLogLibraryPath
    }
  }, (function(_this) {
    return function(err, result) {
      if (result == null) {
        result = {};
      }
      sandbox.kill();
      return _this.sandboxedHookResultsHandler(err, data, result, callback);
    };
  })(this));
}
```
- example usage
```shell
...
    } else if (hook.length === 2) {
      hook(data, function() {
        return callback();
      });
    }
  }
  if (typeof hook === 'string') {
    return this.runSandboxedHookFromString(hook, data, callback);
  }
};

TransactionRunner.prototype.runHook = function(hook, data, callback) {
  if (typeof hook === 'function') {
    if (hook.length === 1) {
      hook(data);
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.sandboxedHookResultsHandler"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>sandboxedHookResultsHandler (err, data, results, callback)](#apidoc.element.dredd.transaction_runner.prototype.sandboxedHookResultsHandler)
- description and source-code
```javascript
sandboxedHookResultsHandler = function (err, data, results, callback) {
  var i, key, len, log, ref, ref1, value;
  if (results == null) {
    results = {};
  }
  if (err) {
    return callback(err);
  }
  ref = results.data || {};
  for (key in ref) {
    value = ref[key];
    data[key] = value;
  }
  this.hookStash = results.stash;
  if (this.logs == null) {
    this.logs = [];
  }
  ref1 = results.logs || [];
  for (i = 0, len = ref1.length; i < len; i++) {
    log = ref1[i];
    this.logs.push(log);
  }
  while (Date.now() - results.now < 0) {}
  callback();
}
```
- example usage
```shell
...
    }
  }, (function(_this) {
    return function(err, result) {
      if (result == null) {
        result = {};
      }
      sandbox.kill();
      return _this.sandboxedHookResultsHandler(err, data, result, callback);
    };
  })(this));
};

TransactionRunner.prototype.runLegacyHook = function(hook, data, callback) {
  if (typeof hook === 'function') {
    if (hook.length === 1) {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.sandboxedWrappedCode"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>sandboxedWrappedCode (hookCode)](#apidoc.element.dredd.transaction_runner.prototype.sandboxedWrappedCode)
- description and source-code
```javascript
sandboxedWrappedCode = function (hookCode) {
  return "// run the hook\nvar log = _log.bind(null, _logs);\n\nvar _func = " + hookCode + ";\n_func(_data);\n\n// setup the return
 object\nvar output = {};\noutput[\"data\"] = _data;\noutput[\"stash\"] = stash;\noutput[\"logs\"] = _logs;\noutput[\"now\"] = Date.now();\noutput;";
}
```
- example usage
```shell
...

TransactionRunner.prototype.sandboxedWrappedCode = function(hookCode) {
  return "// run the hook\nvar log = _log.bind(null, _logs);\n\nvar _func = " + hookCode + ";\n_func(_data);\n\n// setup the return
 object\nvar output = {};\noutput[\"data\"] = _data;\noutput[\"stash\"] = stash;\noutput[\"logs\"] = _logs;\noutput[\"now\"] = Date.now();\noutput;";
};

TransactionRunner.prototype.runSandboxedHookFromString = function(hookString, data, callback) {
  var sandbox, wrappedCode;
  wrappedCode = this.sandboxedWrappedCode(hookString);
  sandbox = new Pitboss(wrappedCode, {
    timeout: 500
  });
  return sandbox.run({
    context: {
      '_data': data,
      '_logs': [],
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.setContentLength"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>setContentLength (transaction)](#apidoc.element.dredd.transaction_runner.prototype.setContentLength)
- description and source-code
```javascript
setContentLength = function (transaction) {
  var body, calculatedContentLengthValue, contentLengthHeaderName, contentLengthValue, headers;
  headers = transaction.request.headers;
  body = transaction.request.body;
  contentLengthHeaderName = caseless(headers).has('Content-Length');
  if (contentLengthHeaderName) {
    contentLengthValue = parseInt(headers[contentLengthHeaderName], 10);
    if (body) {
      calculatedContentLengthValue = Buffer.byteLength(body);
      if (contentLengthValue !== calculatedContentLengthValue) {
        logger.warn("Specified Content-Length header is " + contentLengthValue + ", but the real body length is " + calculatedContentLengthValue
 + ". Using " + calculatedContentLengthValue + " instead.");
        return headers[contentLengthHeaderName] = calculatedContentLengthValue;
      }
    } else if (contentLengthValue !== 0) {
      logger.warn("Specified Content-Length header is " + contentLengthValue + ", but the real body length is 0. Using 0 instead
.");
      return headers[contentLengthHeaderName] = 0;
    }
  } else {
    return headers['Content-Length'] = body ? Buffer.byteLength(body) : 0;
  }
}
```
- example usage
```shell
...
  } else {
    return headers['Content-Length'] = body ? Buffer.byteLength(body) : 0;
  }
};

TransactionRunner.prototype.performRequestAndValidate = function(test, transaction, hooks, callback) {
  var error, handleRequest, requestOptions;
  this.setContentLength(transaction);
  requestOptions = this.getRequestOptionsFromTransaction(transaction);
  handleRequest = (function(_this) {
    return function(err, res, body) {
      var real;
      if (err) {
        logger.debug('Requesting tested server errored:', ("" + err) || err.code);
        test.title = transaction.id;
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.skipTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>skipTransaction (transaction, reason)](#apidoc.element.dredd.transaction_runner.prototype.skipTransaction)
- description and source-code
```javascript
skipTransaction = function (transaction, reason) {
  var base;
  transaction.skip = true;
  this.ensureTransactionResultsGeneralSection(transaction);
  if (reason) {
    transaction.results.general.results.push({
      severity: 'warning',
      message: reason
    });
  }
  if (transaction.test == null) {
    transaction.test = this.createTest(transaction);
  }
  transaction.test.status = 'skip';
  if (reason) {
    transaction.test.message = reason;
  }
  return (base = transaction.test).results != null ? base.results : base.results = transaction.results;
}
```
- example usage
```shell
...
test = this.createTest(transaction);
logger.debug('Emitting to reporters: test start');
this.configuration.emitter.emit('test start', test, function() {});
this.ensureTransactionResultsGeneralSection(transaction);
if (transaction.skip) {
  logger.verbose('HTTP transaction was marked in hooks as to be skipped. Skipping');
  transaction.test = test;
  this.skipTransaction(transaction, 'Skipped in before hook');
  return callback();
} else if (transaction.fail) {
  logger.verbose('HTTP transaction was marked in hooks as to be failed. Reporting as failed');
  transaction.test = test;
  this.failTransaction(transaction, "Failed in before hook: " + transaction.fail);
  return callback();
} else if (this.configuration.options['dry-run']) {
...
```

#### <a name="apidoc.element.dredd.transaction_runner.prototype.validateTransaction"></a>[function <span class="apidocSignatureSpan">dredd.transaction_runner.prototype.</span>validateTransaction (test, transaction, callback)](#apidoc.element.dredd.transaction_runner.prototype.validateTransaction)
- description and source-code
```javascript
validateTransaction = function (test, transaction, callback) {
  var configuration;
  configuration = this.configuration;
  logger.verbose('Validating HTTP transaction by Gavel.js');
  logger.debug('Determining whether HTTP transaction is valid (getting boolean verdict)');
  return gavel.isValid(transaction.real, transaction.expected, 'response', function(isValidError, isValid) {
    if (isValidError) {
      logger.debug('Gavel.js validation errored:', isValidError);
      this.emitError(isValidError, test);
    }
    test.title = transaction.id;
    test.actual = transaction.real;
    test.expected = transaction.expected;
    test.request = transaction.request;
    if (isValid) {
      test.status = 'pass';
    } else {
      test.status = 'fail';
    }
    logger.debug('Validating HTTP transaction (getting verbose validation result)');
    return gavel.validate(transaction.real, transaction.expected, 'response', function(validateError, gavelResult) {
      var gavelError, i, len, message, rawValidatorOutput, ref, ref1, results, sectionName, validatorOutput;
      if (!isValidError && validateError) {
        logger.debug('Gavel.js validation errored:', validateError);
        this.emitError(validateError, test);
      }
      message = '';
      ref = gavelResult || {};
      for (sectionName in ref) {
        if (!hasProp.call(ref, sectionName)) continue;
        validatorOutput = ref[sectionName];
        if (sectionName !== 'version') {
          ref1 = validatorOutput.results || [];
          for (i = 0, len = ref1.length; i < len; i++) {
            gavelError = ref1[i];
            message += sectionName + ": " + gavelError.message + "\n";
          }
        }
      }
      test.message = message;
      results = transaction.results || {};
      for (sectionName in gavelResult) {
        if (!hasProp.call(gavelResult, sectionName)) continue;
        rawValidatorOutput = gavelResult[sectionName];
        if (!(sectionName !== 'version')) {
          continue;
        }
        if (results[sectionName] == null) {
          results[sectionName] = {};
        }
        validatorOutput = clone(rawValidatorOutput);
        if (results[sectionName].results) {
          validatorOutput.results = validatorOutput.results.concat(results[sectionName].results);
        }
        results[sectionName] = validatorOutput;
      }
      transaction.results = results;
      test.results = transaction.results;
      test.valid = isValid;
      transaction.test = test;
      return callback();
    });
  });
}
```
- example usage
```shell
...
        return callback(_this.hookHandlerError);
      }
      logger.verbose('Running \'beforeValidation\' hooks');
      return _this.runHooksForData(hooks != null ? hooks.beforeValidationHooks[transaction.name] : void 0, transaction, false, function
() {
        if (_this.hookHandlerError) {
          return callback(_this.hookHandlerError);
        }
        return _this.validateTransaction(test, transaction, callback);
      });
    });
  };
})(this);
if (transaction.request['body'] && this.isMultipart(requestOptions)) {
  this.replaceLineFeedInBody(transaction, requestOptions);
}
...
```



# <a name="apidoc.module.dredd.which"></a>[module dredd.which](#apidoc.module.dredd.which)

#### <a name="apidoc.element.dredd.which.which"></a>[function <span class="apidocSignatureSpan">dredd.</span>which (command)](#apidoc.element.dredd.which.which)
- description and source-code
```javascript
which = function (command) {
  var e;
  try {
    which.sync(command);
    return true;
  } catch (error) {
    e = error;
    return false;
  }
}
```
- example usage
```shell
...
};

HooksWorkerClient.prototype.setCommandAndCheckForExecutables = function(callback) {
  var gobin, msg, parsedArgs;
  if (this.language === 'ruby') {
    this.handlerCommand = 'dredd-hooks-ruby';
    this.handlerCommandArgs = [];
    if (!which.which(this.handlerCommand)) {
      msg = "Ruby hooks handler command not found: " + this.handlerCommand + "\nInstall ruby hooks handler by running:\n$ gem install
 dredd_hooks";
      return callback(new Error(msg));
    } else {
      return callback();
    }
  } else if (this.language === 'python') {
    this.handlerCommand = 'dredd-hooks-python';
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
