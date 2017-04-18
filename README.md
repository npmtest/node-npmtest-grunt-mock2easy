# test coverage for  [grunt-mock2easy (v0.4.3)](https://github.com/appLhui/grunt-mock2easy)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-mock2easy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-mock2easy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-mock2easy.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-mock2easy)
#### 通过nodejs的服务实现ajax的跨域访问，利用mockjs动态生成json接口，模拟各种恶略环境测试系统是否健全，测试接口生成接口文档

[![NPM](https://nodei.co/npm/grunt-mock2easy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-mock2easy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-mock2easy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-mock2easy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-mock2easy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-mock2easy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-mock2easy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-mock2easy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-mock2easy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-mock2easy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mofei"
    },
    "bugs": {
        "url": "https://github.com/appLhui/grunt-mock2easy/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "colors": "~0.6.2",
        "mock2easy": ">=0.0.5",
        "underscore": "~1.7.0"
    },
    "description": "通过nodejs的服务实现ajax的跨域访问，利用mockjs动态生成json接口，模拟各种恶略环境测试系统是否健全，测试接口生成接口文档",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "984c2a956114a4eeb6e4796da1013334c3babd1f",
        "size": 1417090,
        "noattachment": false,
        "key": "grunt-mock2easy/-/grunt-mock2easy-0.2.31.tgz",
        "tarball": "https://registry.npmjs.org/grunt-mock2easy/-/grunt-mock2easy-0.4.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "homepage": "https://github.com/appLhui/grunt-mock2easy",
    "keywords": [
        "mock",
        "gruntplugin",
        "mockjs",
        "jsonp",
        "postman"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "/blob/master/LICENSE-MIT"
        }
    ],
    "maintainers": [
        {
            "name": "applelihui"
        },
        {
            "name": "flyinhighwj"
        }
    ],
    "name": "grunt-mock2easy",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": "~0.4.0"
    },
    "publish_time": 1419672078526,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/appLhui/grunt-mock2easy.git"
    },
    "scripts": {
        "build": "browserify -t brfs ./tasks/web/app/app.js -o ./tasks/web/public/bundle.js",
        "test": "grunt test"
    },
    "version": "0.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
