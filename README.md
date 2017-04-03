# api documentation for  [level (v1.6.0)](https://github.com/Level/level)  [![npm package](https://img.shields.io/npm/v/npmdoc-level.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-level) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-level.svg)](https://travis-ci.org/npmdoc/node-npmdoc-level)
#### Fast & simple storage - a Node.js-style LevelDB wrapper (a convenience package bundling LevelUP & LevelDOWN)

[![NPM](https://nodei.co/npm/level.png?downloads=true)](https://www.npmjs.com/package/level)

[![apidoc](https://npmdoc.github.io/node-npmdoc-level/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-level_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-level/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-level/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-level/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Level/level/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "email": "john@chesl.es",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "email": "dominic.tarr@gmail.com",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "email": "max@maxogden.com",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "email": "ralphtheninja@riseup.net",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "email": "david.bjorklund@gmail.com",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "email": "julian@juliangruber.com",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "email": "paolo@async.ly",
            "url": "https://github.com/hij1nx"
        },
        {
            "name": "Anton Whalley",
            "email": "anton.whalley@nearform.com",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "email": "pedro.teixeira@gmail.com",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "email": "mail@substack.net",
            "url": "https://github.com/substack"
        }
    ],
    "dependencies": {
        "level-packager": "~1.2.0",
        "leveldown": "~1.6.0"
    },
    "description": "Fast & simple storage - a Node.js-style LevelDB wrapper (a convenience package bundling LevelUP & LevelDOWN)",
    "devDependencies": {
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3fcbae9163a091668b8ec7a9efd1d2feef1e6621",
        "tarball": "https://registry.npmjs.org/level/-/level-1.6.0.tgz"
    },
    "gitHead": "46b1ee4ae085d0029599054a81be82e182eee7ed",
    "homepage": "https://github.com/Level/level",
    "keywords": [
        "leveldb",
        "stream",
        "database",
        "db",
        "store",
        "storage",
        "json"
    ],
    "license": "MIT",
    "main": "level.js",
    "maintainers": [
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "ralphtheninja",
            "email": "ralphtheninja@riseup.net"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        }
    ],
    "name": "level",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Level/level.git"
    },
    "scripts": {
        "test": "node ./test.js"
    },
    "version": "1.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module level](#apidoc.module.level)
1.  [function <span class="apidocSignatureSpan">level.</span>destroy (location, callback)](#apidoc.element.level.destroy)
1.  [function <span class="apidocSignatureSpan">level.</span>repair (location, callback)](#apidoc.element.level.repair)



# <a name="apidoc.module.level"></a>[module level](#apidoc.module.level)

#### <a name="apidoc.element.level.destroy"></a>[function <span class="apidocSignatureSpan">level.</span>destroy (location, callback)](#apidoc.element.level.destroy)
- description and source-code
```javascript
destroy = function (location, callback) {
  leveldown[m](location, callback || function () {})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.level.repair"></a>[function <span class="apidocSignatureSpan">level.</span>repair (location, callback)](#apidoc.element.level.repair)
- description and source-code
```javascript
repair = function (location, callback) {
  leveldown[m](location, callback || function () {})
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
