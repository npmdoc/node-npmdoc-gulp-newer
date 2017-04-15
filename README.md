# api documentation for  [gulp-newer (v1.3.0)](https://github.com/tschaub/gulp-newer)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-newer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-newer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-newer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-newer)
#### Only pass through newer source files

[![NPM](https://nodei.co/npm/gulp-newer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-newer)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Schaub",
        "url": "http://tschaub.net/"
    },
    "bugs": {
        "url": "https://github.com/tschaub/gulp-newer/issues"
    },
    "dependencies": {
        "glob": "^7.0.3",
        "gulp-util": "^3.0.7",
        "kew": "^0.7.0"
    },
    "description": "Only pass through newer source files",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.7.1",
        "eslint-config-tschaub": "^6.0.0",
        "gulp": "^3.9.1",
        "mocha": "^3.1.0",
        "mock-fs": "^3.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d50ecacbb822eda492b57324a6c85a07fd9a55c1",
        "tarball": "https://registry.npmjs.org/gulp-newer/-/gulp-newer-1.3.0.tgz"
    },
    "eslintConfig": {
        "extends": "tschaub"
    },
    "gitHead": "7e41955b90d00c7a5848bdc0d21cc27072a60d35",
    "homepage": "https://github.com/tschaub/gulp-newer",
    "keywords": [
        "gulp",
        "gulpplugin",
        "newer",
        "mtime"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tschaub"
        }
    ],
    "name": "gulp-newer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tschaub/gulp-newer.git"
    },
    "scripts": {
        "pretest": "eslint index.js spec.js",
        "test": "mocha spec.js"
    },
    "version": "1.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-newer](#apidoc.module.gulp-newer)
1.  [function <span class="apidocSignatureSpan"></span>gulp-newer (options)](#apidoc.element.gulp-newer.gulp-newer)
1.  [function <span class="apidocSignatureSpan">gulp-newer.</span>toString ()](#apidoc.element.gulp-newer.toString)



# <a name="apidoc.module.gulp-newer"></a>[module gulp-newer](#apidoc.module.gulp-newer)

#### <a name="apidoc.element.gulp-newer.gulp-newer"></a>[function <span class="apidocSignatureSpan"></span>gulp-newer (options)](#apidoc.element.gulp-newer.gulp-newer)
- description and source-code
```javascript
gulp-newer = function (options) {
  return new Newer(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-newer.toString"></a>[function <span class="apidocSignatureSpan">gulp-newer.</span>toString ()](#apidoc.element.gulp-newer.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
