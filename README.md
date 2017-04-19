# npmtest-formsy-react

#### test coverage for  [formsy-react (v0.19.2)](https://github.com/christianalfoni/formsy-react#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-formsy-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-formsy-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-formsy-react.svg)](https://travis-ci.org/npmtest/node-npmtest-formsy-react)

#### A form input builder and validator for React JS

[![NPM](https://nodei.co/npm/formsy-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/formsy-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-formsy-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-formsy-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-formsy-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-formsy-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-formsy-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-formsy-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-formsy-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-formsy-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-formsy-react/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-formsy-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-formsy-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-formsy-react/build/test-report.html](https://npmtest.github.io/node-npmtest-formsy-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-formsy-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-formsy-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-formsy-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-formsy-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-formsy-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-formsy-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-formsy-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-formsy-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christian Alfoni"
    },
    "bugs": {
        "url": "https://github.com/christianalfoni/formsy-react/issues"
    },
    "dependencies": {
        "form-data-to-object": "^0.2.0"
    },
    "description": "A form input builder and validator for React JS",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "jsdom": "^6.5.1",
        "nodeunit": "^0.9.1",
        "react": "^15.0.0",
        "react-addons-pure-render-mixin": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "sinon": "^1.17.3",
        "webpack": "^1.12.14",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7fa818ff93c8c07195486c4d2e42b6da0c0ee4a3",
        "tarball": "https://registry.npmjs.org/formsy-react/-/formsy-react-0.19.2.tgz"
    },
    "gitHead": "0628d9787954d93111f7e47286ccb3f5afa5e00e",
    "homepage": "https://github.com/christianalfoni/formsy-react#readme",
    "keywords": [
        "react",
        "form",
        "forms",
        "validation",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "aesopwolf"
        },
        {
            "name": "christianalfoni"
        },
        {
            "name": "semigradsky"
        }
    ],
    "name": "formsy-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/christianalfoni/formsy-react.git"
    },
    "scripts": {
        "deploy": "NODE_ENV=production webpack -p --config webpack.production.config.js",
        "examples": "webpack-dev-server --config examples/webpack.config.js --content-base examples",
        "prepublish": "babel ./src/ -d ./lib/",
        "test": "babel-node testrunner"
    },
    "version": "0.19.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
