# api documentation for  [jsbarcode (v3.5.9)](https://github.com/lindell/JsBarcode#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsbarcode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsbarcode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsbarcode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsbarcode)
#### JsBarcode is a customizable barcode generator with support for multiple barcode formats.

[![NPM](https://nodei.co/npm/jsbarcode.png?downloads=true)](https://www.npmjs.com/package/jsbarcode)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-jsbarcode_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Johan Lindell"
    },
    "bin": {
        "barcodes": "bin/barcodes",
        "Barcode.js": "bin/barcodes/Barcode.js",
        "codabar": "bin/barcodes/codabar",
        "index.js": "bin/renderers/index.js",
        "CODE128": "bin/barcodes/CODE128",
        "CODE128_AUTO.js": "bin/barcodes/CODE128/CODE128_AUTO.js",
        "CODE128.js": "bin/barcodes/CODE128/CODE128.js",
        "CODE128A.js": "bin/barcodes/CODE128/CODE128A.js",
        "CODE128B.js": "bin/barcodes/CODE128/CODE128B.js",
        "CODE128C.js": "bin/barcodes/CODE128/CODE128C.js",
        "CODE39": "bin/barcodes/CODE39",
        "EAN_UPC": "bin/barcodes/EAN_UPC",
        "ean_encoder.js": "bin/barcodes/EAN_UPC/ean_encoder.js",
        "EAN13.js": "bin/barcodes/EAN_UPC/EAN13.js",
        "EAN2.js": "bin/barcodes/EAN_UPC/EAN2.js",
        "EAN5.js": "bin/barcodes/EAN_UPC/EAN5.js",
        "EAN8.js": "bin/barcodes/EAN_UPC/EAN8.js",
        "UPC.js": "bin/barcodes/EAN_UPC/UPC.js",
        "GenericBarcode": "bin/barcodes/GenericBarcode",
        "index.tmp.js": "bin/barcodes/index.tmp.js",
        "ITF": "bin/barcodes/ITF",
        "ITF14": "bin/barcodes/ITF14",
        "MSI": "bin/barcodes/MSI",
        "checksums.js": "bin/barcodes/MSI/checksums.js",
        "MSI.js": "bin/barcodes/MSI/MSI.js",
        "MSI10.js": "bin/barcodes/MSI/MSI10.js",
        "MSI1010.js": "bin/barcodes/MSI/MSI1010.js",
        "MSI11.js": "bin/barcodes/MSI/MSI11.js",
        "MSI1110.js": "bin/barcodes/MSI/MSI1110.js",
        "pharmacode": "bin/barcodes/pharmacode",
        "exceptions": "bin/exceptions",
        "ErrorHandler.js": "bin/exceptions/ErrorHandler.js",
        "exceptions.js": "bin/exceptions/exceptions.js",
        "help": "bin/help",
        "fixOptions.js": "bin/help/fixOptions.js",
        "getOptionsFromElement.js": "bin/help/getOptionsFromElement.js",
        "getRenderProperties.js": "bin/help/getRenderProperties.js",
        "linearizeEncodings.js": "bin/help/linearizeEncodings.js",
        "merge.js": "bin/help/merge.js",
        "optionsFromStrings.js": "bin/help/optionsFromStrings.js",
        "JsBarcode.js": "bin/JsBarcode.js",
        "options": "bin/options",
        "defaults.js": "bin/options/defaults.js",
        "renderers": "bin/renderers",
        "canvas.js": "bin/renderers/canvas.js",
        "shared.js": "bin/renderers/shared.js",
        "svg.js": "bin/renderers/svg.js"
    },
    "bugs": {
        "url": "https://github.com/lindell/JsBarcode/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "JsBarcode.js",
                "barcodes"
            ],
            "data-cover-never": [
                "GenericBarcode",
                "node_modules"
            ]
        }
    },
    "dependencies": {},
    "description": "JsBarcode is a customizable barcode generator with support for multiple barcode formats.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.5",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-es2015-classes": "^6.6.5",
        "babel-plugin-transform-runtime": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "blanket": "^1.2.3",
        "canvas": "^1.0.0",
        "coveralls": "^2.11.6",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-bump": "^2.1.0",
        "gulp-clean": "^0.3.2",
        "gulp-concat": "^2.6.0",
        "gulp-eslint": "^3.0.1",
        "gulp-git": "^1.7.1",
        "gulp-header": "^1.7.1",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.5.3",
        "gzip-size": "^3.0.0",
        "mocha": "^3.0.0",
        "mocha-lcov-reporter": "^1.2.0",
        "publish-release": "^1.2.0",
        "request": "^2.72.0",
        "run-sequence": "^1.1.5",
        "webpack": "^2.1.0-beta.5",
        "webpack-stream": "^3.1.0"
    },
    "directories": {
        "example": "example",
        "test": "test",
        "lib": "src",
        "bin": "bin"
    },
    "dist": {
        "shasum": "337e15a1bb5ce6fc0828f245d32e4148442a1c2a",
        "tarball": "https://registry.npmjs.org/jsbarcode/-/jsbarcode-3.5.9.tgz"
    },
    "gitHead": "b6b6af25d013e2c0767bb5febe267205a61f85be",
    "homepage": "https://github.com/lindell/JsBarcode#readme",
    "keywords": [
        "barcode",
        "canvas",
        "code128",
        "upc",
        "ean",
        "itf",
        "msi",
        "pharmacode"
    ],
    "license": "MIT",
    "main": "./bin/JsBarcode.js",
    "maintainers": [
        {
            "name": "lindell",
            "email": "johan@lindell.me"
        }
    ],
    "name": "jsbarcode",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lindell/JsBarcode.git"
    },
    "scripts": {
        "build": "gulp compile",
        "coverage": "mocha test/node/ -r blanket -R html-cov > test/coverage.html",
        "coveralls": "NODE_ENV=test YOURPACKAGE_COVERAGE=1 ./node_modules/.bin/mocha test/node/ --require blanket --reporter mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js",
        "test": "gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec"
    },
    "typings": "./jsbarcode.d.ts",
    "version": "3.5.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module jsbarcode](#apidoc.module.jsbarcode)
1.  [function <span class="apidocSignatureSpan">jsbarcode.</span>getModule (name)](#apidoc.element.jsbarcode.getModule)
1.  object <span class="apidocSignatureSpan">jsbarcode.</span>shared

#### [module jsbarcode.shared](#apidoc.module.jsbarcode.shared)
1.  [function <span class="apidocSignatureSpan">jsbarcode.shared.</span>minifiedFilename (name)](#apidoc.element.jsbarcode.shared.minifiedFilename)



# <a name="apidoc.module.jsbarcode"></a>[module jsbarcode](#apidoc.module.jsbarcode)

#### <a name="apidoc.element.jsbarcode.getModule"></a>[function <span class="apidocSignatureSpan">jsbarcode.</span>getModule (name)](#apidoc.element.jsbarcode.getModule)
- description and source-code
```javascript
getModule = function (name) {
	return _barcodes2.default[name];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jsbarcode.shared"></a>[module jsbarcode.shared](#apidoc.module.jsbarcode.shared)

#### <a name="apidoc.element.jsbarcode.shared.minifiedFilename"></a>[function <span class="apidocSignatureSpan">jsbarcode.shared.</span>minifiedFilename (name)](#apidoc.element.jsbarcode.shared.minifiedFilename)
- description and source-code
```javascript
minifiedFilename = function (name){
	return "JsBarcode." + name + ".min.js";
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
