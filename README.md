# api documentation for  [should (v11.2.1)](https://github.com/shouldjs/should.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-should.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-should) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-should.svg)](https://travis-ci.org/npmdoc/node-npmdoc-should)
#### test framework agnostic BDD-style assertions

[![NPM](https://nodei.co/npm/should.png?downloads=true)](https://www.npmjs.com/package/should)

[![apidoc](https://npmdoc.github.io/node-npmdoc-should/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-should_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-should/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-should/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-should/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bugs": {
        "url": "https://github.com/shouldjs/should.js/issues"
    },
    "dependencies": {
        "should-equal": "^1.0.0",
        "should-format": "^3.0.2",
        "should-type": "^1.4.0",
        "should-type-adaptors": "^1.0.1",
        "should-util": "^1.0.0"
    },
    "description": "test framework agnostic BDD-style assertions",
    "devDependencies": {
        "bluebird": "^3.0.6",
        "eslint": "^3.0.0",
        "eslint-config-shouldjs": "^1.0.0",
        "mocha": "latest",
        "mocha-better-spec-reporter": "latest",
        "rollup": "^0.41.4",
        "rollup-plugin-node-resolve": "^2.0.0",
        "zuul": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "90f55145552d01cfc200666e4e818a1c9670eda2",
        "tarball": "https://registry.npmjs.org/should/-/should-11.2.1.tgz"
    },
    "files": [
        "cjs/*",
        "es6/*",
        "as-function.js",
        "index.js",
        "should.js",
        "LICENSE",
        "*.md"
    ],
    "gitHead": "52b984f2c9212278091f9570cf2fe4d6bb79396f",
    "homepage": "https://github.com/shouldjs/should.js",
    "keywords": [
        "test",
        "bdd",
        "assert",
        "should"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        },
        {
            "name": "gjohnson",
            "email": "gjj391@gmail.com"
        },
        {
            "name": "travisjeffery",
            "email": "tj@travisjeffery.com"
        },
        {
            "name": "btd",
            "email": "bardadymchik@gmail.com"
        }
    ],
    "name": "should",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shouldjs/should.js.git"
    },
    "scripts": {
        "browser": "rollup -c rollup.config.js  --output ./should.js",
        "build": "npm run cjs && npm run es6",
        "cjs": "rollup --format=cjs --output=cjs/should.js lib/should.js",
        "es6": "rollup --format=es --output=es6/should.js lib/should.js",
        "prepublish": "npm run build && npm run browser",
        "pretest": "npm run build",
        "test": "mocha -R mocha-better-spec-reporter --color --check-leaks ./test/*.test.js ./test/**/*.test.js",
        "zuul": "zuul -- ./test/**/*.test.js ./test/*.test.js"
    },
    "version": "11.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
