# npmtest-backbone.marionette

#### basic test coverage for  [backbone.marionette (v3.2.0)](https://marionettejs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-backbone.marionette.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-backbone.marionette) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-backbone.marionette.svg)](https://travis-ci.org/npmtest/node-npmtest-backbone.marionette)

#### The Backbone Framework

[![NPM](https://nodei.co/npm/backbone.marionette.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/backbone.marionette)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-backbone.marionette/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone.marionette/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-backbone.marionette/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-backbone.marionette/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-backbone.marionette/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-backbone.marionette/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-backbone.marionette/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-backbone.marionette/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-backbone.marionette/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone.marionette/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-backbone.marionette/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-backbone.marionette/build/test-report.html](https://npmtest.github.io/node-npmtest-backbone.marionette/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-backbone.marionette/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-backbone.marionette/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-backbone.marionette/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-backbone.marionette/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-backbone.marionette/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-backbone.marionette/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-backbone.marionette/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-backbone.marionette/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "backbone.marionette",
    "description": "The Backbone Framework",
    "version": "3.2.0",
    "homepage": "https://marionettejs.com/",
    "main": "lib/backbone.marionette.js",
    "keywords": [
        "backbone",
        "plugin",
        "marionette",
        "composite",
        "architecture",
        "single",
        "page",
        "app",
        "client",
        "browser"
    ],
    "license": "MIT",
    "scripts": {
        "build": "gulp build",
        "esfix": "gulp esfix",
        "coverage": "gulp coverage",
        "coveralls": "gulp coveralls",
        "test": "gulp",
        "test-browser": "gulp test-browser",
        "test-cross-browser": "gulp test-cross-browser",
        "test-cypress": "gulp cypress-run",
        "test-cypress-ci": "gulp cypress-ci",
        "test-lodash": "USE_LODASH=1 gulp"
    },
    "author": {
        "name": "Derick Bailey",
        "url": "http://derickbailey.com/"
    },
    "bugs": {
        "url": "https://github.com/marionettejs/backbone.marionette/issues"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/marionettejs/backbone.marionette.git"
    },
    "github": "https://github.com/marionettejs/backbone.marionette",
    "dependencies": {
        "backbone.radio": "^2.0.0"
    },
    "peerDependencies": {
        "backbone": "~1.3.3",
        "underscore": "~1.8.3"
    },
    "devDependencies": {
        "babel-core": "6.17.0",
        "babel-eslint": "7.0.0",
        "babel-plugin-transform-regenerator": "6.16.1",
        "babel-polyfill": "6.16.0",
        "babel-preset-es2015": "6.16.0",
        "babel-register": "6.16.3",
        "backbone": "1.2.1 - 1.3.x",
        "chai": "3.5.0",
        "chai-jq": "0.0.9",
        "cypress-cli": "^0.12.0",
        "easy-sauce": "0.4.1",
        "eslint": "3.7.1",
        "gulp": "3.9.1",
        "gulp-coveralls": "0.1.4",
        "gulp-eslint": "3.0.1",
        "gulp-file": "0.3.0",
        "gulp-filter": "4.0.0",
        "gulp-if": "^2.0.1",
        "gulp-istanbul": "1.1.1",
        "gulp-lintspaces": "0.5.0",
        "gulp-livereload": "3.8.1",
        "gulp-mocha": "3.0.1",
        "gulp-plumber": "1.1.0",
        "gulp-rename": "1.2.2",
        "gulp-sourcemaps": "2.1.1",
        "gulp-uglify": "2.0.0",
        "gulp-util": "3.0.7",
        "isparta": "4.0.0",
        "jquery": "3.1.0",
        "jsdom": "9.6.0",
        "lodash": "^4.17.3",
        "mocha": "3.1.2",
        "opn": "4.0.2",
        "rollup": "0.36.3",
        "rollup-plugin-babel": "2.6.1",
        "rollup-plugin-commonjs": "5.0.5",
        "rollup-plugin-json": "2.0.2",
        "rollup-plugin-multi-entry": "2.0.1",
        "rollup-plugin-node-globals": "1.0.9",
        "rollup-plugin-node-resolve": "2.0.0",
        "run-sequence": "1.2.2",
        "sinon": "1.17.6",
        "sinon-chai": "2.8.0",
        "underscore": "1.8 - 1.8.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
