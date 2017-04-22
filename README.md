# npmdoc-node-gyp

#### api documentation for  [node-gyp (v3.6.0)](https://github.com/nodejs/node-gyp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-gyp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-gyp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-gyp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-gyp)

#### Node.js native addon build tool

[![NPM](https://nodei.co/npm/node-gyp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gyp)

- [https://npmdoc.github.io/node-npmdoc-node-gyp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gyp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gyp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gyp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-gyp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-gyp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "url": "http://tootallnate.net"
    },
    "bin": {
        "node-gyp": "./bin/node-gyp.js"
    },
    "bugs": {
        "url": "https://github.com/nodejs/node-gyp/issues"
    },
    "dependencies": {
        "fstream": "^1.0.0",
        "glob": "^7.0.3",
        "graceful-fs": "^4.1.2",
        "minimatch": "^3.0.2",
        "mkdirp": "^0.5.0",
        "nopt": "2 || 3",
        "npmlog": "0 || 1 || 2 || 3 || 4",
        "osenv": "0",
        "request": "2",
        "rimraf": "2",
        "semver": "~5.3.0",
        "tar": "^2.0.0",
        "which": "1"
    },
    "description": "Node.js native addon build tool",
    "devDependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.0.0",
        "require-inject": "~1.3.0",
        "tape": "~4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7474f63a3a0501161dda0b6341f022f14c423fa6",
        "tarball": "https://registry.npmjs.org/node-gyp/-/node-gyp-3.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "8d04acfdf59ff1015d209feb23acd88d593095a1",
    "homepage": "https://github.com/nodejs/node-gyp#readme",
    "installVersion": 9,
    "keywords": [
        "native",
        "addon",
        "module",
        "c",
        "c++",
        "bindings",
        "gyp"
    ],
    "license": "MIT",
    "main": "./lib/node-gyp.js",
    "maintainers": [
        {
            "name": "TooTallNate"
        },
        {
            "name": "bnoordhuis"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "isaacs"
        },
        {
            "name": "rvagg"
        },
        {
            "name": "tootallnate"
        }
    ],
    "name": "node-gyp",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/nodejs/node-gyp.git"
    },
    "scripts": {
        "test": "tape test/test-*"
    },
    "version": "3.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
