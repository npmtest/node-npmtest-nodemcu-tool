# npmtest-nodemcu-tool

#### basic test coverage for  [nodemcu-tool (v2.0.4)](https://github.com/AndiDittrich/NodeMCU-Tool)  [![npm package](https://img.shields.io/npm/v/npmtest-nodemcu-tool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodemcu-tool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodemcu-tool.svg)](https://travis-ci.org/npmtest/node-npmtest-nodemcu-tool)

#### Command line tool to upload and manage files on your NodeMCU / ESP8266 Module.

[![NPM](https://nodei.co/npm/nodemcu-tool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodemcu-tool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodemcu-tool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodemcu-tool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodemcu-tool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodemcu-tool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodemcu-tool/build/test-report.html](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodemcu-tool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andi Dittrich",
        "url": "http://andidittrich.de"
    },
    "bin": {
        "nodemcu-tool": "bin/nodemcu-tool.js"
    },
    "bugs": {
        "url": "https://github.com/AndiDittrich/NodeMCU-Tool/issues"
    },
    "dependencies": {
        "cli-progress": "^1.2.0",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "logging-facility": "^1.1.0",
        "prompt": "^0.2.14",
        "serialport": "^4.0.0"
    },
    "description": "Command line tool to upload and manage files on your NodeMCU / ESP8266 Module.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5ae20727229999967a2114201ce37ba5bc19b638",
        "tarball": "https://registry.npmjs.org/nodemcu-tool/-/nodemcu-tool-2.0.4.tgz"
    },
    "files": [
        "bin",
        "lib",
        "helloworld.lua",
        "CHANGED.md",
        "LICENSE.md",
        "README.md"
    ],
    "gitHead": "e30bc34713e8d8ad108e8b48303760a59349dc45",
    "homepage": "https://github.com/AndiDittrich/NodeMCU-Tool",
    "keywords": [
        "cli",
        "lua",
        "terminal",
        "nodemcu",
        "esp8266",
        "wifi",
        "serial",
        "upload",
        "embedded"
    ],
    "license": "MIT",
    "main": "./lib/NodeMCU-Tool.js",
    "maintainers": [
        {
            "name": "andidittrich"
        }
    ],
    "name": "nodemcu-tool",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andidittrich/NodeMCU-Tool.git"
    },
    "scripts": {},
    "version": "2.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
