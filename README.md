# npmdoc-console-io

#### basic api documentation for  [console-io (v3.0.11)](http://cloudcmd.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-console-io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-console-io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-console-io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-console-io)

#### Web console

[![NPM](https://nodei.co/npm/console-io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/console-io)

- [https://npmdoc.github.io/node-npmdoc-console-io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-console-io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-console-io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-console-io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-console-io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-console-io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "coderaiser",
        "url": "https://github.com/coderaiser"
    },
    "bin": {
        "console": "bin/console.js",
        "console_": "legacy/bin/console.js"
    },
    "bugs": {
        "url": "https://github.com/cloudcmd/console/issues"
    },
    "dependencies": {
        "currify": "^2.0.0",
        "debug": "^2.3.0",
        "express": "^4.14.0",
        "join-io": "^1.4.0",
        "mollify": "^1.0.3",
        "rendy": "^1.1.0",
        "socket.io": "^1.5.0",
        "spawnify": "^3.0.0",
        "tildify": "^1.2.0"
    },
    "description": "Web console",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-plugin-transform-object-assign": "^6.22.0",
        "babel-preset-es2015": "^6.18.0",
        "bower": "^1.5.1",
        "eslint": "^3.10.2",
        "redrun": "^5.9.3"
    },
    "directories": {},
    "dist": {
        "shasum": "85a7cd1ab554e1abf01c7bc92fd299bc265f676e",
        "tarball": "https://registry.npmjs.org/console-io/-/console-io-3.0.11.tgz"
    },
    "gitHead": "f0152339d576c5aa4c00f2122cd412596b563c0f",
    "homepage": "http://cloudcmd.io",
    "keywords": [
        "console",
        "terminal",
        "express"
    ],
    "license": "MIT",
    "main": "server/index.js",
    "maintainers": [
        {
            "name": "coderaiser"
        }
    ],
    "name": "console-io",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cloudcmd/console.git"
    },
    "scripts": {
        "6to5:bin": "babel bin -d legacy/bin",
        "6to5:lib": "babel server -d server_",
        "build": "redrun 6to5:* legacy:*",
        "legacy:index": "echo \"module.exports = require('../server_');\" > legacy/index.js",
        "lint": "redrun lint:*",
        "lint:eslint-bin": "eslint --rule 'no-console:0' bin",
        "lint:eslint-lib": "eslint --config .client.eslintrc lib",
        "wisdom": "npm run build"
    },
    "version": "3.0.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
