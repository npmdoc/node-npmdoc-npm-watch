# api documentation for  [npm-watch (v0.1.8)](https://github.com/grncdr/npm-watch)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-watch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-watch)
#### run scripts from package.json when files change

[![NPM](https://nodei.co/npm/npm-watch.png?downloads=true)](https://www.npmjs.com/package/npm-watch)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-watch/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-npm-watch_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-watch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen Sugden",
        "email": "me@stephensugden.com"
    },
    "bin": {
        "npm-watch": "./cli.js"
    },
    "bugs": {
        "url": "git://github.com/grncdr/npm-watch/issues"
    },
    "dependencies": {
        "nodemon": "^1.3.8",
        "through2": "^2.0.0"
    },
    "description": "run scripts from package.json when files change",
    "devDependencies": {
        "crlf": "^1.1.0",
        "markdown-code-blocks": "0.0.1",
        "tape": "~2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "18caddb1f769e21c896e6ba79168aed8e0da7eb8",
        "tarball": "https://registry.npmjs.org/npm-watch/-/npm-watch-0.1.8.tgz"
    },
    "gitHead": "fb34eea74c6dd932ab5cd5527026d386cdbf90c8",
    "homepage": "https://github.com/grncdr/npm-watch",
    "keywords": [
        "npm",
        "watch",
        "nodemon",
        "monitor"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "grncdr",
            "email": "glurgle@gmail.com"
        },
        {
            "name": "jackwanders",
            "email": "johnwanderson@gmail.com"
        },
        {
            "name": "moos",
            "email": "mooster@42at.com"
        },
        {
            "name": "mordzuber",
            "email": "mez613@gmail.com"
        }
    ],
    "name": "npm-watch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/grncdr/npm-watch.git"
    },
    "scripts": {
        "demo": "markdown-code-blocks -t bash < README.md",
        "exclusions": "bash -c echo 'An extension'",
        "prepublish": "crlf --set=LF cli.js watch-package.js"
    },
    "version": "0.1.8",
    "watch": {
        "test": [
            "watch-package.js",
            "test/*.js"
        ],
        "exclusions": {
            "patterns": "*",
            "extensions": "nothing",
            "ignore": "ignored.js"
        }
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm-watch](#apidoc.module.npm-watch)



# <a name="apidoc.module.npm-watch"></a>[module npm-watch](#apidoc.module.npm-watch)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
