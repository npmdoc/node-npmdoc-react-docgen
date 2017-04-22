# npmdoc-react-docgen

#### api documentation for  [react-docgen (v2.14.1)](https://github.com/reactjs/react-docgen#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-docgen.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-docgen) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-docgen.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-docgen)

#### A CLI and toolkit to extract information from React components for documentation generation.

[![NPM](https://nodei.co/npm/react-docgen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-docgen)

- [https://npmdoc.github.io/node-npmdoc-react-docgen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-docgen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-docgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-docgen/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-docgen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-docgen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Kling"
    },
    "bin": {
        "react-docgen": "bin/react-docgen.js"
    },
    "bugs": {
        "url": "https://github.com/reactjs/react-docgen/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "babel-runtime": "^6.9.2",
        "babylon": "~5.8.3",
        "commander": "^2.9.0",
        "doctrine": "^2.0.0",
        "node-dir": "^0.1.10",
        "recast": "^0.11.5"
    },
    "description": "A CLI and toolkit to extract information from React components for documentation generation.",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^18.0.0",
        "babel-plugin-transform-object-rest-spread": "^6.23.0",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-preset-env": "^1.1.8",
        "babel-preset-flow": "^6.23.0",
        "cross-spawn": "^5.0.0",
        "eslint": "^3.2.2",
        "flow-bin": "^0.39.0",
        "jest": "^18.1.0",
        "rimraf": "^2.3.2",
        "temp": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "29810af1b181957c989390f18048a12c11812169",
        "tarball": "https://registry.npmjs.org/react-docgen/-/react-docgen-2.14.1.tgz"
    },
    "gitHead": "2ef2253bbbdf7ed83be672a40696f6855dcb09ff",
    "homepage": "https://github.com/reactjs/react-docgen#readme",
    "jest": {
        "setupTestFrameworkScriptFile": "<rootDir>/tests/setupTestFramework.js",
        "testPathDirs": [
            "bin",
            "src"
        ],
        "testRegex": "/__tests__/.*-test\\.js$"
    },
    "keywords": [
        "react",
        "documentation-generation"
    ],
    "license": "BSD-3-Clause",
    "main": "dist/main.js",
    "maintainers": [
        {
            "name": "fkling"
        }
    ],
    "name": "react-docgen",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-docgen.git"
    },
    "scripts": {
        "build": "rimraf dist/ && babel src/ --out-dir dist/ --ignore __tests__,__mocks__",
        "check": "npm run lint && npm run flow && npm test",
        "flow": "flow",
        "lint": "eslint src/",
        "prepublish": "npm run build",
        "preversion": "npm run lint",
        "test": "jest",
        "watch": "babel src/ --out-dir dist/ --watch"
    },
    "version": "2.14.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
