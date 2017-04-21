# npmtest-pdfjs

#### basic test coverage for  [pdfjs (v2.0.0-alpha.1)](https://github.com/rkusa/pdfjs)  [![npm package](https://img.shields.io/npm/v/npmtest-pdfjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pdfjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pdfjs.svg)](https://travis-ci.org/npmtest/node-npmtest-pdfjs)

#### A Portable Document Format (PDF) generation library targeting both the server- and client-side.

[![NPM](https://nodei.co/npm/pdfjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pdfjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pdfjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pdfjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pdfjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pdfjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pdfjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pdfjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pdfjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pdfjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pdfjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pdfjs/build/test-report.html](https://npmtest.github.io/node-npmtest-pdfjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pdfjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pdfjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdfjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pdfjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pdfjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pdfjs",
    "author": "Markus Ast <npm.m@rkusa.st>",
    "version": "2.0.0-alpha.1",
    "description": "A Portable Document Format (PDF) generation library targeting both the server- and client-side.",
    "keywords": [
        "pdf",
        "generator"
    ],
    "license": "MIT",
    "homepage": "https://github.com/rkusa/pdfjs",
    "bugs": "https://github.com/rkusa/pdfjs/issues",
    "main": "lib/",
    "scripts": {
        "test": "node --harmony-async-await test/index.js test/pdfs/**/*.js"
    },
    "dependencies": {
        "linebreak": "^0.3.0",
        "opentype.js": "^0.6.2",
        "unorm": "^1.4.1",
        "uuid": "^3.0.1"
    },
    "devDependencies": {
        "tape": "^4.6.3"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/rkusa/pdfjs.git"
    },
    "engines": {
        "node": ">=7"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
