# npmdoc-wavi

#### basic api documentation for  [wavi (v2.1.3)](https://github.com/bakunin95/wavi#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-wavi.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wavi) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wavi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wavi)

#### Generate a class diagram for node.js web application inspired by the Web Application Extension (WAE) for UML. Document your application with wavi.

[![NPM](https://nodei.co/npm/wavi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wavi)

- [https://npmdoc.github.io/node-npmdoc-wavi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wavi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wavi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wavi/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wavi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wavi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "bakunin95"
    },
    "bin": {
        "wavi": "bin/wavi"
    },
    "bugs": {
        "url": "https://github.com/bakunin95/wavi/issues"
    },
    "dependencies": {
        "acorn": "^4.0.4",
        "acorn-umd": "^0.4.0",
        "async": "^2.1.4",
        "babel-polyfill": "^6.20.0",
        "babel-runtime": "^6.20.0",
        "cheerio": "^0.22.0",
        "co": "^4.6.0",
        "css": "^2.2.1",
        "escope": "^3.6.0",
        "esrecurse": "^4.1.0",
        "estraverse": "^4.2.0",
        "fs": "0.0.2",
        "mkdirp": "^0.5.1",
        "path": "^0.12.7",
        "underscore": "^1.8.3"
    },
    "description": "Generate a class diagram for node.js web application inspired by the Web Application Extension (WAE) for UML. Document your application with wavi.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-loader": "^6.2.10",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-es2016": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-preset-stage-2": "^6.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e479aae3b07e68eba08e776ec15ee2d857bc35df",
        "tarball": "https://registry.npmjs.org/wavi/-/wavi-2.1.3.tgz"
    },
    "email": "jugle66@hotmail.com",
    "gitHead": "a0b1ec4210f968392293ff7d0e9ad1357e243724",
    "homepage": "https://github.com/bakunin95/wavi#readme",
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "bakunin95"
        }
    ],
    "name": "wavi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bakunin95/wavi.git"
    },
    "script": {
        "transpile": "babel --source-maps --out-dir=es5 src"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "url": "https://github.com/bakunin95/wavi",
    "version": "2.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
