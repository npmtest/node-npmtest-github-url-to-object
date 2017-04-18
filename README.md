# test coverage for  [github-url-to-object (v3.1.0)](https://github.com/zeke/github-url-to-object#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-github-url-to-object.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-github-url-to-object) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-github-url-to-object.svg)](https://travis-ci.org/npmtest/node-npmtest-github-url-to-object)
#### Extract user, repo, and other interesting properties from GitHub URLs

[![NPM](https://nodei.co/npm/github-url-to-object.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/github-url-to-object)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-github-url-to-object/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-github-url-to-object/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-github-url-to-object/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-github-url-to-object/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-github-url-to-object/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-github-url-to-object/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-github-url-to-object/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-github-url-to-object/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-github-url-to-object/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-github-url-to-object/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-github-url-to-object/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-github-url-to-object/build/test-report.html](https://npmtest.github.io/node-npmtest-github-url-to-object/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-github-url-to-object/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-github-url-to-object/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-github-url-to-object/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-github-url-to-object/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "zeke"
    },
    "browser": {
        "url": "./url-browser"
    },
    "bugs": {
        "url": "https://github.com/zeke/github-url-to-object/issues"
    },
    "dependencies": {
        "is-url": "^1.1.0"
    },
    "description": "Extract user, repo, and other interesting properties from GitHub URLs",
    "devDependencies": {
        "browserify": "^13.0.1",
        "buble": "^0.15.2",
        "mocha": "^2.5.3",
        "standard": "^7.1.2",
        "uglify-js": "^2.4.15"
    },
    "directories": {},
    "dist": {
        "shasum": "160a5d55ad7cf0459e0757f7912d718076b7ed7d",
        "tarball": "https://registry.npmjs.org/github-url-to-object/-/github-url-to-object-3.1.0.tgz"
    },
    "gitHead": "272793ef9cab8df426718ad15589fcce6b61fdad",
    "homepage": "https://github.com/zeke/github-url-to-object#readme",
    "keywords": [
        "github",
        "url",
        "repo"
    ],
    "license": "MIT",
    "main": "dist/commonjs.js",
    "maintainers": [
        {
            "name": "zeke"
        }
    ],
    "name": "github-url-to-object",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeke/github-url-to-object.git"
    },
    "scripts": {
        "build": "browserify index.js --standalone gh | buble > dist/gh.js; buble index.js > dist/commonjs.js",
        "deploy": "npm run build && git subtree push --prefix dist origin gh-pages && open https://zeke.github.io/github-url-to-object",
        "test": "mocha && standard"
    },
    "standard": {
        "ignore": [
            "dist"
        ]
    },
    "version": "3.1.0",
    "website": "https://zeke.github.io/github-url-to-object"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
