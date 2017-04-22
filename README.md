# npmtest-brackets

#### basic test-coverage for  [brackets (v0.5.8)](https://github.com/rabchev/brackets-server)  [![npm package](https://img.shields.io/npm/v/npmtest-brackets.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-brackets) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-brackets.svg)](https://travis-ci.org/npmtest/node-npmtest-brackets)

#### Brackets Server is a server for providing hosted version of the popular code editor Brackets.

[![NPM](https://nodei.co/npm/brackets.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/brackets)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-brackets/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-brackets/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-brackets/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-brackets/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-brackets/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-brackets/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-brackets/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-brackets/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-brackets/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-brackets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-brackets/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-brackets/build/test-report.html](https://npmtest.github.io/node-npmtest-brackets/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-brackets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-brackets/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brackets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-brackets/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-brackets/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Boyan Rabchev"
    },
    "bin": {
        "brackets": "./bin/run.js",
        "brackets-server": "./bin/run.js"
    },
    "bugs": {
        "url": "https://github.com/rabchev/brackets-server/issues"
    },
    "contributors": [
        {
            "name": "Boyan Rabchev"
        }
    ],
    "dependencies": {
        "commander": "^2.3.0",
        "glob": "^4.0.6",
        "mkdirp": "^0.5.0",
        "ncp": "^1.0.0",
        "open": "^0.0.5",
        "rimraf": "^2.2.8",
        "send": "^0.9.3",
        "socket.io": "1.1.0"
    },
    "description": "Brackets Server is a server for providing hosted version of the popular code editor Brackets.",
    "devDependencies": {
        "chai": "*",
        "grunt": "*",
        "grunt-concurrent": "*",
        "grunt-contrib-clean": "*",
        "grunt-contrib-compress": "*",
        "grunt-contrib-concat": "*",
        "grunt-contrib-copy": "*",
        "grunt-contrib-htmlmin": "*",
        "grunt-contrib-less": "0.8.2",
        "grunt-contrib-requirejs": "*",
        "grunt-node-inspector": "*",
        "grunt-release": "*",
        "grunt-replace": "*",
        "grunt-shell": "*",
        "grunt-simple-mocha": "*",
        "grunt-targethtml": "*",
        "grunt-text-replace": "*",
        "grunt-usemin": "0.1.11",
        "load-grunt-tasks": "*",
        "mocha": "*",
        "q": "0.9.2",
        "shelljs": "^0.3.0",
        "sinon-chai": "*",
        "supertest": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "7ecb9847cab882f7ccb68b12a2d8d426430d1195",
        "tarball": "https://registry.npmjs.org/brackets/-/brackets-0.5.8.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "a848dee514079e80ecba2d430e99abd863f554b0",
    "homepage": "https://github.com/rabchev/brackets-server",
    "keywords": [
        "brackets",
        "node",
        "nodejs",
        "code",
        "editor",
        "web",
        "project",
        "application",
        "management",
        "dev",
        "development",
        "javascript",
        "html",
        "css",
        "ide"
    ],
    "license": {
        "type": "MIT",
        "url": "http://github.com/rabchev/brackets-server/blob/master/LICENSE"
    },
    "main": "./lib/server",
    "maintainers": [
        {
            "name": "rabchev"
        }
    ],
    "name": "brackets",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rabchev/brackets-server.git"
    },
    "scripts": {
        "postinstall": "node lib/post-install.js",
        "test": "grunt test"
    },
    "version": "0.5.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
