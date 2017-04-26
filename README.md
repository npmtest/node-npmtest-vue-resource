# npmtest-vue-resource

#### basic test coverage for  [vue-resource (v1.3.1)](https://github.com/pagekit/vue-resource#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-resource.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-resource) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-resource.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-resource)

#### The HTTP client for Vue.js

[![NPM](https://nodei.co/npm/vue-resource.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-resource)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-resource/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-resource/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-resource/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-resource/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-resource/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-vue-resource/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-vue-resource/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-resource/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-resource/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-resource/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-resource/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-resource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-resource/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-resource/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-resource/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-resource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-resource/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-resource/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-resource/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-resource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-resource/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-resource/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-resource/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "got": false
    },
    "bugs": {
        "url": "https://github.com/pagekit/vue-resource/issues"
    },
    "dependencies": {
        "got": "^6.7.1"
    },
    "description": "The HTTP client for Vue.js",
    "devDependencies": {
        "buble": "^0.15.2",
        "buble-loader": "^0.4.1",
        "generate-release": "^0.11.0",
        "jasmine-core": "^2.5.2",
        "jest": "^19.0.2",
        "replace-in-file": "^2.5.0",
        "rollup": "^0.41.6",
        "rollup-plugin-buble": "^0.15.0",
        "uglify-js": "^2.8.22",
        "vue": "^2.2.6",
        "webpack": "^2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "bf2f7b70bfe21b397c9d7607878f776a3acea2cf",
        "tarball": "https://registry.npmjs.org/vue-resource/-/vue-resource-1.3.1.tgz"
    },
    "gitHead": "2cd014dec1dce477f2c7b22e29ce6179d472f2d3",
    "homepage": "https://github.com/pagekit/vue-resource#readme",
    "keywords": [
        "vue",
        "xhr",
        "http",
        "ajax"
    ],
    "license": "MIT",
    "main": "dist/vue-resource.common.js",
    "maintainers": [
        {
            "name": "yyx990803"
        },
        {
            "name": "steffans"
        }
    ],
    "module": "dist/vue-resource.es2015.js",
    "name": "vue-resource",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pagekit/vue-resource.git"
    },
    "scripts": {
        "build": "node build/build.js",
        "release": "node build/release.js",
        "test": "jest --env=node",
        "webpack": "webpack --config test/webpack.config.js"
    },
    "version": "1.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
