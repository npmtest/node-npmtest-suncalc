# test coverage for  [suncalc (v1.8.0)](https://github.com/mourner/suncalc)  [![npm package](https://img.shields.io/npm/v/npmtest-suncalc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-suncalc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-suncalc.svg)](https://travis-ci.org/npmtest/node-npmtest-suncalc)
#### A tiny JavaScript library for calculating sun/moon positions and phases.

[![NPM](https://nodei.co/npm/suncalc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/suncalc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-suncalc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-suncalc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-suncalc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-suncalc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-suncalc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-suncalc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-suncalc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-suncalc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-suncalc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-suncalc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-suncalc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-suncalc/build/test-report.html](https://npmtest.github.io/node-npmtest-suncalc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-suncalc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-suncalc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-suncalc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-suncalc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-suncalc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-suncalc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-suncalc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-suncalc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vladimir Agafonkin"
    },
    "bugs": {
        "url": "https://github.com/mourner/suncalc/issues"
    },
    "dependencies": {},
    "description": "A tiny JavaScript library for calculating sun/moon positions and phases.",
    "devDependencies": {
        "eslint": "^3.12.2",
        "eslint-config-mourner": "^2.0.1",
        "tap": "^8.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1d9898109563078750f4994a959e654d876acbf5",
        "tarball": "https://registry.npmjs.org/suncalc/-/suncalc-1.8.0.tgz"
    },
    "eslintConfig": {
        "extends": "mourner",
        "rules": {
            "indent": 0,
            "array-bracket-spacing": 0,
            "strict": 0,
            "brace-style": 0
        },
        "env": {
            "amd": true
        }
    },
    "gitHead": "b08d1f6f8e56a3c0d85469d6cf0ff8675cba40a5",
    "homepage": "https://github.com/mourner/suncalc",
    "jshintConfig": {
        "quotmark": "single",
        "trailing": true,
        "unused": true
    },
    "keywords": [
        "sun",
        "astronomy",
        "math",
        "calculation",
        "sunrise",
        "sunset",
        "twilight",
        "moon",
        "illumination"
    ],
    "main": "suncalc.js",
    "maintainers": [
        {
            "name": "mourner"
        }
    ],
    "name": "suncalc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mourner/suncalc.git"
    },
    "scripts": {
        "cov": "tap test.js --cov",
        "pretest": "eslint suncalc.js test.js",
        "test": "tap test.js"
    },
    "version": "1.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
