# npmdoc-appdmg

#### api documentation for  appdmg (v0.4.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-appdmg.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-appdmg) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-appdmg.svg)](https://travis-ci.org/npmdoc/node-npmdoc-appdmg)

####

[![NPM](https://nodei.co/npm/appdmg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/appdmg)

- [https://npmdoc.github.io/node-npmdoc-appdmg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-appdmg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-appdmg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-appdmg/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-appdmg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-appdmg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "appdmg",
    "version": "0.4.5",
    "license": "MIT",
    "author": "Linus Unnebäck <linus@folkdatorn.se>",
    "bin": "bin/appdmg.js",
    "main": "index.js",
    "preferGlobal": true,
    "dependencies": {
        "async": "^1.4.2",
        "cp-file": "^3.1.0",
        "ds-store": "^0.1.5",
        "execa": "^0.4.0",
        "fs-temp": "^1.0.0",
        "fs-xattr": "^0.1.14",
        "image-size": "^0.5.0",
        "is-my-json-valid": "^2.13.1",
        "minimist": "^1.1.3",
        "parse-color": "^1.0.0",
        "repeat-string": "^1.5.4"
    },
    "engines": {
        "node": ">=0.12"
    },
    "os": [
        "darwin"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/LinusU/node-appdmg.git"
    },
    "scripts": {
        "test": "standard && mocha -b"
    },
    "devDependencies": {
        "capture-window": "^0.1.3",
        "looks-same": "^2.1.0",
        "mocha": "^2.2.5",
        "standard": "^7.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
