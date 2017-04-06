# api documentation for  [brace (v0.10.0)](https://github.com/thlorenz/brace)  [![npm package](https://img.shields.io/npm/v/npmdoc-brace.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-brace) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-brace.svg)](https://travis-ci.org/npmdoc/node-npmdoc-brace)
#### browserify compatible version of the ace editor.

[![NPM](https://nodei.co/npm/brace.png?downloads=true)](https://www.npmjs.com/package/brace)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brace/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-brace_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brace/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-brace/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-brace/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "email": "thlorenz@gmx.de",
        "url": "http://thlorenz.com"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/brace/issues"
    },
    "dependencies": {
        "w3c-blob": "0.0.1"
    },
    "description": "browserify compatible version of the ace editor.",
    "devDependencies": {
        "browserify": "~4.2.0",
        "opener": "~1.3.0",
        "shelljs": "~0.2.6",
        "tape": "~4.0.0",
        "uglify-js": "~2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "edef4eb9b0928ba1ee5f717ffc157749a6dd5d76",
        "tarball": "https://registry.npmjs.org/brace/-/brace-0.10.0.tgz"
    },
    "engine": {
        "node": ">=0.6"
    },
    "gitHead": "78c89b5dc6c381dcbd1d4433f1b7d96aec1fe3fd",
    "homepage": "https://github.com/thlorenz/brace",
    "keywords": [
        "ace",
        "editor",
        "browser",
        "package",
        "bundle",
        "inline",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "thlorenz",
            "email": "thlorenz@gmx.de"
        }
    ],
    "name": "brace",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/brace.git"
    },
    "scripts": {
        "test": "browserify test/*.js > test/bundle.js --debug && opener test/index.html",
        "update": "(cd build && node ./update && node ./update-ts)"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "firefox/21..latest",
            "firefox/nightly",
            "chrome/26..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "typings": "index.d.ts",
    "version": "0.10.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module brace](#apidoc.module.brace)



# <a name="apidoc.module.brace"></a>[module brace](#apidoc.module.brace)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
