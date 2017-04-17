# test coverage for  [eslint-plugin-ava (v4.2.0)](https://github.com/avajs/eslint-plugin-ava#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-ava.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-ava) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-ava.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-ava)
#### ESLint rules for AVA

[![NPM](https://nodei.co/npm/eslint-plugin-ava.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-ava)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-ava/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-ava/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-ava/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-ava/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-ava/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-ava/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/avajs/eslint-plugin-ava/issues"
    },
    "dependencies": {
        "arrify": "^1.0.1",
        "deep-strict-equal": "^0.2.0",
        "enhance-visitors": "^1.0.0",
        "espree": "^3.1.3",
        "espurify": "^1.5.0",
        "multimatch": "^2.1.0",
        "pkg-up": "^1.0.0",
        "req-all": "^1.0.0"
    },
    "description": "ESLint rules for AVA",
    "devDependencies": {
        "ava": "*",
        "babel-eslint": "^7.1.0",
        "coveralls": "^2.11.9",
        "eslint": "^3.7.1",
        "eslint-ava-rule-tester": "^2.0.0",
        "js-combinatorics": "^0.5.0",
        "nyc": "^10.0.0",
        "pify": "^2.3.0",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "12e4664659c1fae7895fa3f346c313ceb8907c77",
        "tarball": "https://registry.npmjs.org/eslint-plugin-ava/-/eslint-plugin-ava-4.2.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "create-ava-rule.js",
        "util.js",
        "rules"
    ],
    "gitHead": "8c8d3fa1b97d341c7f852249f041808160e9de51",
    "homepage": "https://github.com/avajs/eslint-plugin-ava#readme",
    "keywords": [
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "ava",
        "test",
        "runner",
        "assert",
        "asserts",
        "assertion",
        "mocha"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ava"
        },
        {
            "name": "jamestalmage"
        },
        {
            "name": "jfmengels"
        },
        {
            "name": "novemberborn"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "vdemedes"
        }
    ],
    "name": "eslint-plugin-ava",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=3.6"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/avajs/eslint-plugin-ava.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && nyc ava"
    },
    "version": "4.2.0",
    "xo": {
        "esnext": true,
        "rules": {
            "prefer-template": "off"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
