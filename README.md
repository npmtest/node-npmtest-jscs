# test coverage for  [jscs (v3.0.7)](http://jscs.info)  [![npm package](https://img.shields.io/npm/v/npmtest-jscs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jscs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jscs.svg)](https://travis-ci.org/npmtest/node-npmtest-jscs)
#### JavaScript Code Style

[![NPM](https://nodei.co/npm/jscs.png?downloads=true)](https://www.npmjs.com/package/jscs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jscs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jscs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jscs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jscs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jscs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jscs/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscs/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-jscs/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-jscs/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-jscs%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jscs/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jscs/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-jscs%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jscs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jscs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jscs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marat Dulin",
        "email": "mdevils@yandex.ru",
        "url": "https://github.com/jscs-dev/node-jscs/graphs/contributors"
    },
    "bin": {
        "jscs": "./bin/jscs"
    },
    "bugs": {
        "url": "https://github.com/jscs-dev/node-jscs/issues"
    },
    "dependencies": {
        "chalk": "~1.1.0",
        "cli-table": "~0.3.1",
        "commander": "~2.9.0",
        "cst": "^0.4.3",
        "estraverse": "^4.1.0",
        "exit": "~0.1.2",
        "glob": "^5.0.1",
        "htmlparser2": "3.8.3",
        "js-yaml": "~3.4.0",
        "jscs-jsdoc": "^2.0.0",
        "jscs-preset-wikimedia": "~1.0.0",
        "jsonlint": "~1.6.2",
        "lodash": "~3.10.0",
        "minimatch": "~3.0.0",
        "natural-compare": "~1.2.2",
        "pathval": "~0.1.1",
        "prompt": "~0.2.14",
        "reserved-words": "^0.1.1",
        "resolve": "^1.1.6",
        "strip-bom": "^2.0.0",
        "strip-json-comments": "~1.0.2",
        "to-double-quotes": "^2.0.0",
        "to-single-quotes": "^2.0.0",
        "vow": "~0.4.8",
        "vow-fs": "~0.3.4",
        "xmlbuilder": "^3.1.0"
    },
    "description": "JavaScript Code Style",
    "devDependencies": {
        "chai": "^3.3.0",
        "coveralls": "~2.11.2",
        "has-ansi": "~2.0.0",
        "jshint": "~2.8.0",
        "mocha": "^2.2.0",
        "regenerate": "~1.2.1",
        "rewire": "^2.3.1",
        "sinon": "^1.13.0",
        "sinon-chai": "^2.8.0",
        "unicode-7.0.0": "~0.1.5",
        "unit-coverage": "^4.0.1",
        "xml2js": "~0.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "7141b4dff5b86e32d0e99d764b836767c30d201a",
        "tarball": "https://registry.npmjs.org/jscs/-/jscs-3.0.7.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "bin",
        "lib",
        "patterns",
        "presets",
        "LICENSE"
    ],
    "gitHead": "e177990d913aafd3e96870a9202194cbbda05167",
    "homepage": "http://jscs.info",
    "keywords": [
        "code style",
        "formatter",
        "lint",
        "linter",
        "style guide",
        "validate"
    ],
    "license": "MIT",
    "main": "lib/checker",
    "maintainers": [
        {
            "name": "hzoo",
            "email": "hi@henryzoo.com"
        },
        {
            "name": "markelog",
            "email": "markelog@gmail.com"
        },
        {
            "name": "mdevils",
            "email": "mdevils@yandex.ru"
        },
        {
            "name": "mikesherov",
            "email": "mike.sherov@gmail.com"
        },
        {
            "name": "mrjoelkemp",
            "email": "joel@mrjoelkemp.com"
        },
        {
            "name": "qfox",
            "email": "zxqfox@gmail.com"
        }
    ],
    "name": "jscs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jscs-dev/node-jscs.git"
    },
    "scripts": {
        "changelog": "git log 'git describe --tags --abbrev=0'..HEAD --pretty=format:' * %s (%an)' | grep -v 'Merge pull request'",
        "coverage": "unit-coverage run -p common",
        "coverage-html": "unit-coverage run -p common -r html -o coverage.html",
        "coveralls": "unit-coverage run -p common -r lcov -o out.lcov && cat out.lcov | coveralls",
        "integration": "#node test/scripts/integration.js",
        "jscs": "node bin/jscs lib test bin publish",
        "jshint": "jshint .",
        "lint": "npm run jshint && npm run jscs",
        "pretest": "npm run lint",
        "release": "node publish/prepublish && npm test && npm publish",
        "test": "mocha --color",
        "watch": "mocha --color --watch"
    },
    "unit-coverage": {
        "common": [
            "-a",
            "lib",
            "-a",
            "test",
            "-s",
            "lib/**/*.js",
            "-t",
            "test/specs/**/*.js",
            "-e",
            "lib/cli-config.js",
            "-S",
            "relative",
            "-O",
            "sources=lib",
            "-O",
            "tests=test/specs"
        ]
    },
    "version": "3.0.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
