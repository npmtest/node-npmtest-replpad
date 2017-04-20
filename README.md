# npmtest-replpad

#### basic test coverage for  replpad (v0.14.0)  [![npm package](https://img.shields.io/npm/v/npmtest-replpad.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-replpad) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-replpad.svg)](https://travis-ci.org/npmtest/node-npmtest-replpad)

#### Pipes content of files to a node repl whenever they change and adds many more features to enable a highly interactive coding experience.

[![NPM](https://nodei.co/npm/replpad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/replpad)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-replpad/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-replpad/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-replpad/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-replpad/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-replpad/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-replpad/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-replpad/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-replpad/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-replpad/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-replpad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-replpad/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-replpad/build/test-report.html](https://npmtest.github.io/node-npmtest-replpad/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-replpad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-replpad/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-replpad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-replpad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-replpad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-replpad/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-replpad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-replpad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "replpad",
    "version": "0.14.0",
    "description": "Pipes content of files to a node repl whenever they change and adds many more features to enable a highly interactive coding experience.",
    "main": "repreprep.js",
    "bin": {
        "replpad": "./bin/replpad.js"
    },
    "scripts": {
        "test-main": "tap test/",
        "test-0.8": "nave use 0.8 npm run test-main",
        "test-0.10": "nave use 0.10 npm run test-main",
        "test-all": "npm run test-main && npm run test-0.8 && npm run test-0.10",
        "test": "if [ -e $TRAVIS ]; then npm run test-all; else npm run test-main; fi"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/replpad.git"
    },
    "keywords": [
        "node",
        "repl",
        "edit",
        "evaluate",
        "debug",
        "scriptie-talkie",
        "jsdoc",
        "source",
        "doc",
        "documentation"
    ],
    "author": "Thorsten Lorenz <thlorenz@gmx.de> (thlorenz.com)",
    "license": "MIT",
    "dependencies": {
        "anchor-markdown-header": "~0.3.2",
        "ansicolors": "~0.2.1",
        "ansistyles": "~0.1.1",
        "cardinal": "~0.4.2",
        "chokidar": "~0.12.6",
        "escodegen": "0.0.15",
        "esprima": "~1.0.3",
        "find-parent-dir": "~0.1.0",
        "findex": "~0.2.1",
        "function-comment": "~0.2.0",
        "hasinternet": "0.0.0",
        "hermit": "~0.2.2",
        "marked": "~0.2.9",
        "mkdirp": "~0.3.5",
        "mothership": "~0.3.0",
        "msee": "~0.1.1",
        "opener": "~1.3.0",
        "readdirp": "~1.3.0",
        "readline-matchtoken": "~0.1.0",
        "readline-vim": "~0.3.0",
        "request": "~2.12.0",
        "require-like": "~0.1.2",
        "scriptie-talkie": "~0.4.7",
        "xtend": "~2.0.6"
    },
    "devDependencies": {
        "nave": "~0.4.5",
        "tap": "~0.4.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
