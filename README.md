# npmtest-micromatch

#### basic test coverage for  [micromatch (v2.3.11)](https://github.com/jonschlinkert/micromatch)  [![npm package](https://img.shields.io/npm/v/npmtest-micromatch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-micromatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-micromatch.svg)](https://travis-ci.org/npmtest/node-npmtest-micromatch)

#### Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.

[![NPM](https://nodei.co/npm/micromatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/micromatch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-micromatch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-micromatch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-micromatch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-micromatch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-micromatch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-micromatch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-micromatch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-micromatch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-micromatch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-micromatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-micromatch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-micromatch/build/test-report.html](https://npmtest.github.io/node-npmtest-micromatch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-micromatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-micromatch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-micromatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-micromatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-micromatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-micromatch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-micromatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-micromatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "micromatch",
    "description": "Glob matching for javascript/node.js. A drop-in replacement and faster alternative to minimatch and multimatch.",
    "version": "2.3.11",
    "homepage": "https://github.com/jonschlinkert/micromatch",
    "author": "Jon Schlinkert (https://github.com/jonschlinkert)",
    "repository": "jonschlinkert/micromatch",
    "bugs": {
        "url": "https://github.com/jonschlinkert/micromatch/issues"
    },
    "license": "MIT",
    "files": [
        "index.js",
        "lib"
    ],
    "main": "index.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "dependencies": {
        "arr-diff": "^2.0.0",
        "array-unique": "^0.2.1",
        "braces": "^1.8.2",
        "expand-brackets": "^0.1.4",
        "extglob": "^0.3.1",
        "filename-regex": "^2.0.0",
        "is-extglob": "^1.0.0",
        "is-glob": "^2.0.1",
        "kind-of": "^3.0.2",
        "normalize-path": "^2.0.1",
        "object.omit": "^2.0.0",
        "parse-glob": "^3.0.4",
        "regex-cache": "^0.4.2"
    },
    "devDependencies": {
        "benchmarked": "^0.1.4",
        "chalk": "^1.1.1",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.1.1",
        "gulp-format-md": "^0.1.8",
        "gulp-istanbul": "^0.10.1",
        "gulp-mocha": "^2.1.3",
        "minimatch": "^3.0.0",
        "minimist": "^1.2.0",
        "mocha": "^2",
        "multimatch": "^2.0.0",
        "should": "^8",
        "write": "^0.2.1"
    },
    "keywords": [
        "bash",
        "expand",
        "expansion",
        "expression",
        "file",
        "files",
        "filter",
        "find",
        "glob",
        "globbing",
        "globs",
        "globstar",
        "match",
        "matcher",
        "matches",
        "matching",
        "minimatch",
        "multimatch",
        "path",
        "pattern",
        "patterns",
        "regex",
        "regexp",
        "regular",
        "shell",
        "wildcard"
    ],
    "verb": {
        "related": {
            "list": [
                "braces",
                "expand-brackets",
                "expand-range",
                "extglob",
                "fill-range",
                "gulp-micromatch",
                "is-glob",
                "parse-glob"
            ]
        },
        "reflinks": [
            "braces",
            "expand-brackets",
            "extglob",
            "minimatch",
            "multimatch",
            "verb"
        ],
        "toc": false,
        "layout": false,
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
