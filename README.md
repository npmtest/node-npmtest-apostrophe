# npmtest-apostrophe

#### basic test coverage for  [apostrophe (v2.23.1)](https://github.com/punkave/apostrophe#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apostrophe.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apostrophe) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apostrophe.svg)](https://travis-ci.org/npmtest/node-npmtest-apostrophe)

#### The Apostrophe Content Management System.

[![NPM](https://nodei.co/npm/apostrophe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apostrophe)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apostrophe/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apostrophe/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apostrophe/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apostrophe/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apostrophe/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-apostrophe/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-apostrophe/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apostrophe/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apostrophe/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apostrophe/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apostrophe/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apostrophe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apostrophe/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apostrophe/build/test-report.html](https://npmtest.github.io/node-npmtest-apostrophe/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apostrophe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apostrophe/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apostrophe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apostrophe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apostrophe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apostrophe/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apostrophe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apostrophe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "P'unk Avenue LLC"
    },
    "bugs": {
        "url": "https://github.com/punkave/apostrophe/issues"
    },
    "dependencies": {
        "async": "^1.0.0",
        "bless": "^3.0.3",
        "body-parser": "^1.12.0",
        "broadband": "^0.1.1",
        "cheerio": "^0.22.0",
        "clean-css": "^3.0.9",
        "connect-flash": "^0.1.1",
        "connect-mongo": "^1.0.0",
        "connect-multiparty": "^2.0.0",
        "cookie-parser": "^1.3.4",
        "credential": "^1.0.0",
        "cuid": "^1.2.5",
        "deep-get-set": "^0.1.1",
        "diff": "^2.1.0",
        "express": "^4.11.2",
        "express-session": "^1.10.3",
        "glob": "^5.0.0",
        "he": "^0.5.0",
        "i18n": "^0.8.0",
        "joinr": "^1.0.1",
        "launder": "^0.1.1",
        "less": "^2.0.0",
        "less-middleware": "^2.0.0",
        "lodash": "^3.1.0",
        "minimatch": "^3.0.0",
        "mkdirp": "^0.5.0",
        "moment": "^2.9.0",
        "mongodb": "^2.0.0",
        "moog-require": "^0.4.0",
        "nunjucks": "^2.0.0",
        "oembetter": "^0.1.10",
        "passport": "^0.3.0",
        "passport-local": "^1.0.0",
        "path-to-regexp": "^1.2.0",
        "prompt": "^0.2.14",
        "qs": "^5.0.0",
        "regexp-quote": "0.0.0",
        "request": "^2.53.0",
        "rimraf": "^2.5.4",
        "sanitize-html": "^1.7.0",
        "sluggo": "^0.2.0",
        "syntax-error": "^1.1.6",
        "uglify-js": "^2.4.16",
        "underscore.string": "^3.0.2",
        "uploadfs": "^1.1.8",
        "xregexp": "^2.0.0",
        "yargs": "^3.0.0"
    },
    "description": "The Apostrophe Content Management System.",
    "devDependencies": {
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f8a9a787a89574c088ef0dfd75797abc7f576d72",
        "tarball": "https://registry.npmjs.org/apostrophe/-/apostrophe-2.23.1.tgz"
    },
    "gitHead": "f45fb90d3dba1c157aa9e6cce8fa9e7f12bebd8d",
    "homepage": "https://github.com/punkave/apostrophe#readme",
    "keywords": [
        "apostrophe",
        "cms",
        "content management",
        "content management system",
        "punkave"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alexgilbert"
        },
        {
            "name": "austinstarin"
        },
        {
            "name": "boutell"
        },
        {
            "name": "colpanik"
        },
        {
            "name": "grdunn"
        },
        {
            "name": "jimmyh"
        },
        {
            "name": "kyjoya"
        },
        {
            "name": "mcoppola"
        },
        {
            "name": "stuartromanek"
        }
    ],
    "name": "apostrophe",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/punkave/apostrophe.git"
    },
    "scripts": {
        "test": "mocha test/test.js"
    },
    "version": "2.23.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
