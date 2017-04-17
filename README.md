# test coverage for  [ua-parser-js (v0.7.12)](http://github.com/faisalman/ua-parser-js)  [![npm package](https://img.shields.io/npm/v/npmtest-ua-parser-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ua-parser-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ua-parser-js.svg)](https://travis-ci.org/npmtest/node-npmtest-ua-parser-js)
#### Lightweight JavaScript-based user-agent string parser

[![NPM](https://nodei.co/npm/ua-parser-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ua-parser-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ua-parser-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ua-parser-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ua-parser-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ua-parser-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ua-parser-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ua-parser-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ua-parser-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ua-parser-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ua-parser-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ua-parser-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ua-parser-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ua-parser-js/build/test-report.html](https://npmtest.github.io/node-npmtest-ua-parser-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ua-parser-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ua-parser-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ua-parser-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ua-parser-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Faisal Salman",
        "url": "http://faisalman.com"
    },
    "bugs": {
        "url": "https://github.com/faisalman/ua-parser-js/issues"
    },
    "contributors": [
        {
            "name": "Faisal Salman"
        },
        {
            "name": "Benjamin Bertrand"
        },
        {
            "name": "Carl C Von Lewin"
        },
        {
            "name": "Christopher De Cairos"
        },
        {
            "name": "Davit Barbakadze"
        },
        {
            "name": "Dmitry Tyschenko"
        },
        {
            "name": "Douglas Li"
        },
        {
            "name": "Dumitru Uzun"
        },
        {
            "name": "Erik Hesselink"
        },
        {
            "name": "Fabian Becker"
        },
        {
            "name": "Hendrik Helwich"
        },
        {
            "name": "Jackpoll"
        },
        {
            "name": "Jake Mc"
        },
        {
            "name": "John Tantalo"
        },
        {
            "name": "John Yanarella"
        },
        {
            "name": "Jon Buckley"
        },
        {
            "name": "Kendall Buchanan"
        },
        {
            "name": "Lee Treveil"
        },
        {
            "name": "Leonardo"
        },
        {
            "name": "Max Maurer"
        },
        {
            "name": "Michael Hess"
        },
        {
            "name": "OtakuSiD"
        },
        {
            "name": "Ross Noble"
        },
        {
            "name": "Sandro Sonntag"
        }
    ],
    "dependencies": {},
    "description": "Lightweight JavaScript-based user-agent string parser",
    "devDependencies": {
        "jshint": "~1.1.0",
        "mocha": "~1.8.0",
        "requirejs": "^2.3.2",
        "uglify-js": "~1.3.4",
        "verup": "^1.3.x"
    },
    "directories": {
        "dist": "dist",
        "src": "src",
        "test": "test"
    },
    "dist": {
        "shasum": "04c81a99bdd5dc52263ea29d24c6bf8d4818a4bb",
        "tarball": "https://registry.npmjs.org/ua-parser-js/-/ua-parser-js-0.7.12.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "01ae611dfa2d2c2ec3dba79c454538c0ed92e54f",
    "homepage": "http://github.com/faisalman/ua-parser-js",
    "keywords": [
        "user-agent",
        "parser",
        "browser",
        "engine",
        "os",
        "device",
        "cpu"
    ],
    "license": "(GPL-2.0 OR MIT)",
    "main": "src/ua-parser.js",
    "maintainers": [
        {
            "name": "faisalman"
        }
    ],
    "name": "ua-parser-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/faisalman/ua-parser-js.git"
    },
    "scripts": {
        "build": "uglifyjs src/ua-parser.js > dist/ua-parser.min.js --comments '/UAParser\\.js/' && uglifyjs src/ua-parser.js > dist/ua-parser.pack.js --comments '/UAParser\\.js/' --compress --mangle",
        "test": "jshint src/ua-parser.js && mocha -R nyan test/test.js",
        "version": "node ./node_modules/verup 0",
        "verup": "node ./node_modules/verup"
    },
    "title": "UAParser.js",
    "version": "0.7.12",
    "verup": {
        "files": [
            "ua-parser-js.jquery.json",
            "component.json",
            "bower.json",
            "package.js",
            "src/ua-parser.js"
        ],
        "regs": [
            "^((?:\\$|(\\s*\\*\\s*@)|(\\s*(?:var|,)?\\s+))(?:LIBVERSION|version)[\\s\\:='\"]+)([0-9]+(?:\\.[0-9]+){2,2})",
            "^(\\s?\\*.*v)([0-9]+(?:\\.[0-9]+){2,2})"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
