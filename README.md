# npmdoc-express-fileupload

#### api documentation for  [express-fileupload (v0.1.2)](https://github.com/richardgirges/express-fileupload#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-fileupload.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-fileupload) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-fileupload.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-fileupload)

#### Simple express file upload middleware that wraps around Busboy

[![NPM](https://nodei.co/npm/express-fileupload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-fileupload)

- [https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Girges"
    },
    "bugs": {
        "url": "https://github.com/richardgirges/express-fileupload/issues"
    },
    "dependencies": {
        "busboy": "^0.2.14",
        "fs-extra": "^0.22.1",
        "streamifier": "^0.1.1"
    },
    "description": "Simple express file upload middleware that wraps around Busboy",
    "devDependencies": {
        "body-parser": "^1.16.1",
        "coveralls": "^2.11.16",
        "eslint": "^3.15.0",
        "eslint-config-google": "^0.7.1",
        "express": "^4.13.4",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "supertest": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f7ba6f32568a3752e5bbffdcb8f4f047832fa98e",
        "tarball": "https://registry.npmjs.org/express-fileupload/-/express-fileupload-0.1.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "9c885440167a8d743307f93c7d901740dfad219f",
    "homepage": "https://github.com/richardgirges/express-fileupload#readme",
    "keywords": [
        "express",
        "file-upload",
        "upload",
        "forms",
        "multipart",
        "files",
        "busboy",
        "middleware"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "richardgirges"
        }
    ],
    "name": "express-fileupload",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/richardgirges/express-fileupload.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "lint": "eslint ./",
        "test": "istanbul cover _mocha -- -R spec"
    },
    "version": "0.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
