# npmtest-express-paginate

#### basic test coverage for  [express-paginate (v0.2.2)](https://github.com/niftylettuce/express-paginate)  [![npm package](https://img.shields.io/npm/v/npmtest-express-paginate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-paginate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-paginate.svg)](https://travis-ci.org/npmtest/node-npmtest-express-paginate)

#### Node.js pagination middleware and view helpers

[![NPM](https://nodei.co/npm/express-paginate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-paginate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-paginate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-paginate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-paginate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-paginate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-paginate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-paginate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-paginate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-paginate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-paginate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-paginate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-paginate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-paginate/build/test-report.html](https://npmtest.github.io/node-npmtest-express-paginate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-paginate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-paginate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-paginate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-paginate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-paginate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-paginate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-paginate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-paginate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Baugh"
    },
    "bugs": {
        "url": "https://github.com/niftylettuce/express-paginate/issues"
    },
    "contributors": [
        {
            "name": "Esco Obong"
        },
        {
            "name": "Matheus Marchini"
        },
        {
            "name": "Carlo Bernaschina"
        }
    ],
    "dependencies": {
        "lodash.assign": "^3.2.0",
        "lodash.clone": "^3.0.3",
        "lodash.isobject": "^3.0.2",
        "querystring": "^0.2.0"
    },
    "description": "Node.js pagination middleware and view helpers",
    "devDependencies": {
        "async": "^1.4.2",
        "chai": "^1.9.1",
        "istanbul": "^0.3.0",
        "mocha": "^1.21.4",
        "reqres": "^1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "65b1f9de1cb110ff581bd2a8025e9ee1a061df99",
        "tarball": "https://registry.npmjs.org/express-paginate/-/express-paginate-0.2.2.tgz"
    },
    "gitHead": "91a3d4205112343e4ca311fc00bdb13d04c16c4d",
    "homepage": "https://github.com/niftylettuce/express-paginate",
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "niftylettuce"
        }
    ],
    "name": "express-paginate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/niftylettuce/express-paginate.git"
    },
    "scripts": {
        "prepublish": "npm prune",
        "test": "mocha --reporter spec --bail --check-leaks --require test/support/should test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks --require test/support/should  test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks --require test/support/should test/"
    },
    "version": "0.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
