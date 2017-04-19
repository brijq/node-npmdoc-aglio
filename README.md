# npmdoc-aglio

#### api documentation for  [aglio (v2.3.0)](https://github.com/danielgtaylor/aglio#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-aglio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aglio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aglio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aglio)

#### An API Blueprint renderer with theme support

[![NPM](https://nodei.co/npm/aglio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aglio)

- [https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aglio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aglio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aglio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aglio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel G. Taylor"
    },
    "bin": {
        "aglio": "./bin/aglio.js"
    },
    "bugs": {
        "url": "https://github.com/danielgtaylor/aglio/issues"
    },
    "dependencies": {
        "aglio-theme-olio": "^1.6.3",
        "chokidar": "^1.4.1",
        "cli-color": "^1.1.0",
        "drafter": "^1.0.0",
        "pretty-error": "^1.2.0",
        "serve-static": "^1.10.0",
        "socket.io": "^1.3.7",
        "yargs": "^3.31.0"
    },
    "description": "An API Blueprint renderer with theme support",
    "devDependencies": {
        "async": "^1.5.0",
        "coffeelint": "^1.14.2",
        "grunt": "~0.4.5",
        "grunt-coffeelint": "0.0.13",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-mocha-cov": "^0.4.0",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9f7462f01520996415278a02d0e20b36ec96adcc",
        "tarball": "https://registry.npmjs.org/aglio/-/aglio-2.3.0.tgz"
    },
    "gitHead": "df554dc380c0ee6a2c83f8c62c4739491c5dd3c2",
    "homepage": "https://github.com/danielgtaylor/aglio#readme",
    "keywords": [
        "api",
        "blueprint",
        "protagonist",
        "snowcrash",
        "html",
        "parse",
        "markdown"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "danielgtaylor"
        },
        {
            "name": "zdne"
        },
        {
            "name": "pksunkara"
        },
        {
            "name": "kylef"
        }
    ],
    "name": "aglio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielgtaylor/aglio.git"
    },
    "scripts": {
        "prepublish": "grunt compile",
        "test": "grunt test"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
