# npmtest-offline-plugin

#### test coverage for  [offline-plugin (v4.7.0)](https://github.com/NekR/offline-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-offline-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-offline-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-offline-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-offline-plugin)

#### offline-plugin for webpack

[![NPM](https://nodei.co/npm/offline-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/offline-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-offline-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-offline-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-offline-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-offline-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-offline-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-offline-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-offline-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-offline-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-offline-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-offline-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-offline-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-offline-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-offline-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-offline-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-offline-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-offline-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-offline-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-offline-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-offline-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-offline-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-offline-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arthur Stolyar"
    },
    "bugs": {
        "url": "https://github.com/NekR/offline-plugin/issues"
    },
    "buildDependencies": {
        "babel": "^5.8.23"
    },
    "dependencies": {
        "deep-extend": "^0.4.0",
        "ejs": "^2.3.4",
        "loader-utils": "0.2.x",
        "minimatch": "^3.0.3",
        "slash": "^1.0.0"
    },
    "description": "offline-plugin for webpack",
    "devDependencies": {
        "chalk": "^1.1.3",
        "cli-highlight": "^1.1.4",
        "del": "^2.2.2",
        "diff": "^3.0.1",
        "dir-compare": "^1.1.0",
        "eslint": "^3.14.1",
        "on-build-webpack": "^0.1.0",
        "webpack": "1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4c2fca6cd46c6dd7f29fc94ade21e5f82a62c4df",
        "tarball": "https://registry.npmjs.org/offline-plugin/-/offline-plugin-4.7.0.tgz"
    },
    "files": [
        "lib/",
        "tpls/",
        "runtime.js",
        "empty-entry.js"
    ],
    "gitHead": "5f63cd58448a60ccbb5072971f3af9688ba4a7cd",
    "homepage": "https://github.com/NekR/offline-plugin",
    "keywords": [
        "webpack",
        "plugin",
        "offline",
        "cache",
        "caching",
        "storage",
        "service-worker",
        "serviceworker",
        "appcache",
        "application cache",
        "pwa",
        "progressive web apps",
        "app-shell",
        "appshell"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "nekr"
        }
    ],
    "name": "offline-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/NekR/offline-plugin.git"
    },
    "scripts": {
        "build": "babel src/ -d lib/",
        "install:build-deps": "node build/install.js",
        "publish:latest": "npm publish",
        "publish:next": "npm publish --tag=next",
        "release:latest:major": "npm version major && npm run tag && npm run publish:latest",
        "release:latest:minor": "npm version minor && npm run tag && npm run publish:latest",
        "release:latest:patch": "npm version patch && npm run tag && npm run publish:latest",
        "release:next:major": "npm version major && npm run tag && npm run publish:next",
        "release:next:minor": "npm version minor && npm run tag && npm run publish:next",
        "release:next:patch": "npm version patch && npm run tag && npm run publish:next",
        "tag": "git push && git push --tags",
        "test": "node tests/legacy/run && eslint -c configs/eslint.tests.json 'tests/**/**.js'",
        "watch": "npm run build -- --watch"
    },
    "version": "4.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
