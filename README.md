# npmtest-speakeasy

#### basic test coverage for  [speakeasy (v2.0.0)](http://github.com/speakeasyjs/speakeasy)  [![npm package](https://img.shields.io/npm/v/npmtest-speakeasy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-speakeasy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-speakeasy.svg)](https://travis-ci.org/npmtest/node-npmtest-speakeasy)

#### Two-factor authentication for Node.js. One-time passcode generator (HOTP/TOTP) with support for Google Authenticator.

[![NPM](https://nodei.co/npm/speakeasy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/speakeasy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-speakeasy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-speakeasy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-speakeasy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-speakeasy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-speakeasy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-speakeasy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-speakeasy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-speakeasy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-speakeasy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-speakeasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-speakeasy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-speakeasy/build/test-report.html](https://npmtest.github.io/node-npmtest-speakeasy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-speakeasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-speakeasy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-speakeasy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-speakeasy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-speakeasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-speakeasy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-speakeasy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-speakeasy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mark Bao & Speakeasy Contributors"
    },
    "bugs": {
        "url": "https://github.com/speakeasyjs/speakeasy/issues"
    },
    "contributors": [
        {
            "name": "Michael Phan-Ba"
        },
        {
            "name": "Guy Halford-Thompson"
        }
    ],
    "dependencies": {
        "base32.js": "0.0.1"
    },
    "description": "Two-factor authentication for Node.js. One-time passcode generator (HOTP/TOTP) with support for Google Authenticator.",
    "devDependencies": {
        "chai": "^3.4.1",
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.2",
        "jsdoc": "^3.3.1",
        "mocha": "^2.2.5",
        "semistandard": "^7.0.5",
        "snazzy": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "85c91a071b09a5cb8642590d983566165f57613a",
        "tarball": "https://registry.npmjs.org/speakeasy/-/speakeasy-2.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "4e0aa91dee166306e07ea11e371d5a5df95f4391",
    "homepage": "http://github.com/speakeasyjs/speakeasy",
    "keywords": [
        "authentication",
        "google authenticator",
        "hmac",
        "hotp",
        "multi-factor",
        "one-time password",
        "passwords",
        "totp",
        "two factor",
        "two-factor",
        "two-factor authentication"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "markbao"
        }
    ],
    "name": "speakeasy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/speakeasyjs/speakeasy.git"
    },
    "scripts": {
        "cover": "istanbul cover _mocha -- test/* -R spec",
        "doc": "jsdoc -c jsdoc.json && sed -i '' -e 's/․/./g' docs/speakeasy/*/*.html",
        "lint": "semistandard --verbose | snazzy",
        "test": "mocha"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
