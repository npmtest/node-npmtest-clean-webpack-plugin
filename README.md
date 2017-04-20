# npmtest-clean-webpack-plugin

#### basic test coverage for  [clean-webpack-plugin (v0.1.16)](https://github.com/johnagan/clean-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-clean-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clean-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clean-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-clean-webpack-plugin)

#### A webpack plugin to remove your build folder(s) before building

[![NPM](https://nodei.co/npm/clean-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clean-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clean-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clean-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clean-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "clean-webpack-plugin",
    "version": "0.1.16",
    "author": "John Agan <johnagan@gmail.com>",
    "description": "A webpack plugin to remove your build folder(s) before building",
    "homepage": "https://github.com/johnagan/clean-webpack-plugin",
    "license": "MIT",
    "main": "index.js",
    "keywords": [
        "webpack",
        "plugin",
        "clean",
        "node"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/johnagan/clean-webpack-plugin.git"
    },
    "bugs": {
        "url": "https://github.com/johnagan/clean-webpack-plugin/issues"
    },
    "scripts": {
        "test": "mocha --recursive ./test/*_spec.js",
        "test:watch": "npm run test -- --watch",
        "test-travis": "istanbul cover _mocha -- -R spec ./test/*_spec.js"
    },
    "dependencies": {
        "rimraf": "~2.5.1"
    },
    "devDependencies": {
        "chai": "^3.4.1",
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.2",
        "rewire": "^2.5.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
