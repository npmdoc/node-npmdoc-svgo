# api documentation for  [svgo (v0.7.2)](https://github.com/svg/svgo)  [![npm package](https://img.shields.io/npm/v/npmdoc-svgo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-svgo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-svgo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-svgo)
#### Nodejs-based tool for optimizing SVG vector graphics files

[![NPM](https://nodei.co/npm/svgo.png?downloads=true)](https://www.npmjs.com/package/svgo)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svgo/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-svgo_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svgo/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-svgo/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Kir Belevich",
        "email": "kir@soulshine.in",
        "url": "https://github.com/deepsweet"
    },
    "bin": {
        "svgo": "./bin/svgo"
    },
    "bugs": {
        "url": "https://github.com/svg/svgo/issues",
        "email": "kir@soulshine.in"
    },
    "contributors": [
        {
            "name": "Sergey Belov",
            "email": "peimei@ya.ru",
            "url": "http://github.com/arikon"
        },
        {
            "name": "Lev Solntsev",
            "email": "lev.sun@ya.ru",
            "url": "http://github.com/GreLI"
        }
    ],
    "dependencies": {
        "coa": "~1.0.1",
        "colors": "~1.1.2",
        "csso": "~2.3.1",
        "js-yaml": "~3.7.0",
        "mkdirp": "~0.5.1",
        "sax": "~1.2.1",
        "whet.extend": "~0.9.9"
    },
    "description": "Nodejs-based tool for optimizing SVG vector graphics files",
    "devDependencies": {
        "coveralls": "~2.11.14",
        "istanbul": "~0.4.5",
        "mocha": "~3.2.0",
        "mocha-istanbul": "~0.3.0",
        "should": "11.2.0"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib",
        "example": "./examples"
    },
    "dist": {
        "shasum": "9f5772413952135c6fefbf40afe6a4faa88b4bb5",
        "tarball": "https://registry.npmjs.org/svgo/-/svgo-0.7.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "ad053787d019e3efc0e21b7478e5b1c7816b17d6",
    "homepage": "https://github.com/svg/svgo",
    "keywords": [
        "svgo",
        "svg",
        "optimize",
        "minify"
    ],
    "license": "MIT",
    "main": "./lib/svgo.js",
    "maintainers": [
        {
            "name": "deepsweet",
            "email": "kir@soulshine.in"
        },
        {
            "name": "greli",
            "email": "grelimail@gmail.com"
        }
    ],
    "name": "svgo",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/svg/svgo.git"
    },
    "scripts": {
        "jshint": "jshint --show-non-errors .",
        "test": "set NODE_ENV=test && mocha"
    },
    "version": "0.7.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module svgo](#apidoc.module.svgo)
1.  object <span class="apidocSignatureSpan">svgo.</span>_path
1.  object <span class="apidocSignatureSpan">svgo.</span>_transforms
1.  object <span class="apidocSignatureSpan">svgo.</span>addAttributesToSVGElement
1.  object <span class="apidocSignatureSpan">svgo.</span>addClassesToSVGElement
1.  object <span class="apidocSignatureSpan">svgo.</span>cleanupAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>cleanupEnableBackground
1.  object <span class="apidocSignatureSpan">svgo.</span>cleanupIDs
1.  object <span class="apidocSignatureSpan">svgo.</span>cleanupListOfValues
1.  object <span class="apidocSignatureSpan">svgo.</span>cleanupNumericValues
1.  object <span class="apidocSignatureSpan">svgo.</span>collapseGroups
1.  object <span class="apidocSignatureSpan">svgo.</span>convertColors
1.  object <span class="apidocSignatureSpan">svgo.</span>convertPathData
1.  object <span class="apidocSignatureSpan">svgo.</span>convertShapeToPath
1.  object <span class="apidocSignatureSpan">svgo.</span>convertStyleToAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>convertTransform
1.  object <span class="apidocSignatureSpan">svgo.</span>mergePaths
1.  object <span class="apidocSignatureSpan">svgo.</span>minifyStyles
1.  object <span class="apidocSignatureSpan">svgo.</span>moveElemsAttrsToGroup
1.  object <span class="apidocSignatureSpan">svgo.</span>moveGroupAttrsToElems
1.  object <span class="apidocSignatureSpan">svgo.</span>removeAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>removeComments
1.  object <span class="apidocSignatureSpan">svgo.</span>removeDesc
1.  object <span class="apidocSignatureSpan">svgo.</span>removeDimensions
1.  object <span class="apidocSignatureSpan">svgo.</span>removeDoctype
1.  object <span class="apidocSignatureSpan">svgo.</span>removeEditorsNSData
1.  object <span class="apidocSignatureSpan">svgo.</span>removeElementsByAttr
1.  object <span class="apidocSignatureSpan">svgo.</span>removeEmptyAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>removeEmptyContainers
1.  object <span class="apidocSignatureSpan">svgo.</span>removeEmptyText
1.  object <span class="apidocSignatureSpan">svgo.</span>removeHiddenElems
1.  object <span class="apidocSignatureSpan">svgo.</span>removeMetadata
1.  object <span class="apidocSignatureSpan">svgo.</span>removeNonInheritableGroupAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>removeRasterImages
1.  object <span class="apidocSignatureSpan">svgo.</span>removeStyleElement
1.  object <span class="apidocSignatureSpan">svgo.</span>removeTitle
1.  object <span class="apidocSignatureSpan">svgo.</span>removeUnknownsAndDefaults
1.  object <span class="apidocSignatureSpan">svgo.</span>removeUnusedNS
1.  object <span class="apidocSignatureSpan">svgo.</span>removeUselessDefs
1.  object <span class="apidocSignatureSpan">svgo.</span>removeUselessStrokeAndFill
1.  object <span class="apidocSignatureSpan">svgo.</span>removeViewBox
1.  object <span class="apidocSignatureSpan">svgo.</span>removeXMLNS
1.  object <span class="apidocSignatureSpan">svgo.</span>removeXMLProcInst
1.  object <span class="apidocSignatureSpan">svgo.</span>sortAttrs
1.  object <span class="apidocSignatureSpan">svgo.</span>transformsWithOnePath

#### [module svgo._path](#apidoc.module.svgo._path)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>applyTransforms (elem, path, params)](#apidoc.element.svgo._path.applyTransforms)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>computeCubicBoundingBox (xa, ya, xb, yb, xc, yc, xd, yd)](#apidoc.element.svgo._path.computeCubicBoundingBox)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>computeQuadraticBoundingBox (xa, ya, xb, yb, xc, yc)](#apidoc.element.svgo._path.computeQuadraticBoundingBox)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>intersects (path1, path2)](#apidoc.element.svgo._path.intersects)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>js2path (path, data, params)](#apidoc.element.svgo._path.js2path)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>path2js (path)](#apidoc.element.svgo._path.path2js)
1.  [function <span class="apidocSignatureSpan">svgo._path.</span>relative2absolute (data)](#apidoc.element.svgo._path.relative2absolute)

#### [module svgo._transforms](#apidoc.module.svgo._transforms)
1.  [function <span class="apidocSignatureSpan">svgo._transforms.</span>matrixToTransform (transform, params)](#apidoc.element.svgo._transforms.matrixToTransform)
1.  [function <span class="apidocSignatureSpan">svgo._transforms.</span>transform2js (transformString)](#apidoc.element.svgo._transforms.transform2js)
1.  [function <span class="apidocSignatureSpan">svgo._transforms.</span>transformArc (arc, transform)](#apidoc.element.svgo._transforms.transformArc)
1.  [function <span class="apidocSignatureSpan">svgo._transforms.</span>transformsMultiply (transforms)](#apidoc.element.svgo._transforms.transformsMultiply)
1.  object <span class="apidocSignatureSpan">svgo._transforms.</span>mth

#### [module svgo.addAttributesToSVGElement](#apidoc.module.svgo.addAttributesToSVGElement)
1.  boolean <span class="apidocSignatureSpan">svgo.addAttributesToSVGElement.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.addAttributesToSVGElement.</span>fn (data, params)](#apidoc.element.svgo.addAttributesToSVGElement.fn)
1.  string <span class="apidocSignatureSpan">svgo.addAttributesToSVGElement.</span>description
1.  string <span class="apidocSignatureSpan">svgo.addAttributesToSVGElement.</span>type

#### [module svgo.addClassesToSVGElement](#apidoc.module.svgo.addClassesToSVGElement)
1.  boolean <span class="apidocSignatureSpan">svgo.addClassesToSVGElement.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.addClassesToSVGElement.</span>fn (data, params)](#apidoc.element.svgo.addClassesToSVGElement.fn)
1.  string <span class="apidocSignatureSpan">svgo.addClassesToSVGElement.</span>description
1.  string <span class="apidocSignatureSpan">svgo.addClassesToSVGElement.</span>type

#### [module svgo.cleanupAttrs](#apidoc.module.svgo.cleanupAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>fn (item, params)](#apidoc.element.svgo.cleanupAttrs.fn)
1.  object <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>params
1.  string <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>type

#### [module svgo.cleanupEnableBackground](#apidoc.module.svgo.cleanupEnableBackground)
1.  boolean <span class="apidocSignatureSpan">svgo.cleanupEnableBackground.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.cleanupEnableBackground.</span>fn (data)](#apidoc.element.svgo.cleanupEnableBackground.fn)
1.  string <span class="apidocSignatureSpan">svgo.cleanupEnableBackground.</span>description
1.  string <span class="apidocSignatureSpan">svgo.cleanupEnableBackground.</span>type

#### [module svgo.cleanupIDs](#apidoc.module.svgo.cleanupIDs)
1.  boolean <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>fn (data, params)](#apidoc.element.svgo.cleanupIDs.fn)
1.  object <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>params
1.  string <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>type

#### [module svgo.cleanupListOfValues](#apidoc.module.svgo.cleanupListOfValues)
1.  boolean <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>fn (item, params)](#apidoc.element.svgo.cleanupListOfValues.fn)
1.  object <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>params
1.  string <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>description
1.  string <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>type

#### [module svgo.cleanupNumericValues](#apidoc.module.svgo.cleanupNumericValues)
1.  boolean <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>fn (item, params)](#apidoc.element.svgo.cleanupNumericValues.fn)
1.  object <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>params
1.  string <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>description
1.  string <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>type

#### [module svgo.collapseGroups](#apidoc.module.svgo.collapseGroups)
1.  boolean <span class="apidocSignatureSpan">svgo.collapseGroups.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.collapseGroups.</span>fn (item)](#apidoc.element.svgo.collapseGroups.fn)
1.  string <span class="apidocSignatureSpan">svgo.collapseGroups.</span>description
1.  string <span class="apidocSignatureSpan">svgo.collapseGroups.</span>type

#### [module svgo.convertColors](#apidoc.module.svgo.convertColors)
1.  boolean <span class="apidocSignatureSpan">svgo.convertColors.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.convertColors.</span>fn (item, params)](#apidoc.element.svgo.convertColors.fn)
1.  object <span class="apidocSignatureSpan">svgo.convertColors.</span>params
1.  string <span class="apidocSignatureSpan">svgo.convertColors.</span>description
1.  string <span class="apidocSignatureSpan">svgo.convertColors.</span>type

#### [module svgo.convertPathData](#apidoc.module.svgo.convertPathData)
1.  boolean <span class="apidocSignatureSpan">svgo.convertPathData.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.convertPathData.</span>fn (item, params)](#apidoc.element.svgo.convertPathData.fn)
1.  object <span class="apidocSignatureSpan">svgo.convertPathData.</span>params
1.  string <span class="apidocSignatureSpan">svgo.convertPathData.</span>description
1.  string <span class="apidocSignatureSpan">svgo.convertPathData.</span>type

#### [module svgo.convertShapeToPath](#apidoc.module.svgo.convertShapeToPath)
1.  boolean <span class="apidocSignatureSpan">svgo.convertShapeToPath.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.convertShapeToPath.</span>fn (item)](#apidoc.element.svgo.convertShapeToPath.fn)
1.  string <span class="apidocSignatureSpan">svgo.convertShapeToPath.</span>description
1.  string <span class="apidocSignatureSpan">svgo.convertShapeToPath.</span>type

#### [module svgo.convertStyleToAttrs](#apidoc.module.svgo.convertStyleToAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.convertStyleToAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.convertStyleToAttrs.</span>fn (item)](#apidoc.element.svgo.convertStyleToAttrs.fn)
1.  string <span class="apidocSignatureSpan">svgo.convertStyleToAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.convertStyleToAttrs.</span>type

#### [module svgo.convertTransform](#apidoc.module.svgo.convertTransform)
1.  boolean <span class="apidocSignatureSpan">svgo.convertTransform.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.convertTransform.</span>fn (item, params)](#apidoc.element.svgo.convertTransform.fn)
1.  object <span class="apidocSignatureSpan">svgo.convertTransform.</span>params
1.  string <span class="apidocSignatureSpan">svgo.convertTransform.</span>description
1.  string <span class="apidocSignatureSpan">svgo.convertTransform.</span>type

#### [module svgo.mergePaths](#apidoc.module.svgo.mergePaths)
1.  boolean <span class="apidocSignatureSpan">svgo.mergePaths.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.mergePaths.</span>fn (item, params)](#apidoc.element.svgo.mergePaths.fn)
1.  object <span class="apidocSignatureSpan">svgo.mergePaths.</span>params
1.  string <span class="apidocSignatureSpan">svgo.mergePaths.</span>description
1.  string <span class="apidocSignatureSpan">svgo.mergePaths.</span>type

#### [module svgo.minifyStyles](#apidoc.module.svgo.minifyStyles)
1.  boolean <span class="apidocSignatureSpan">svgo.minifyStyles.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.minifyStyles.</span>fn (item, svgoOptions)](#apidoc.element.svgo.minifyStyles.fn)
1.  object <span class="apidocSignatureSpan">svgo.minifyStyles.</span>params
1.  string <span class="apidocSignatureSpan">svgo.minifyStyles.</span>description
1.  string <span class="apidocSignatureSpan">svgo.minifyStyles.</span>type

#### [module svgo.moveElemsAttrsToGroup](#apidoc.module.svgo.moveElemsAttrsToGroup)
1.  boolean <span class="apidocSignatureSpan">svgo.moveElemsAttrsToGroup.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.moveElemsAttrsToGroup.</span>fn (item)](#apidoc.element.svgo.moveElemsAttrsToGroup.fn)
1.  string <span class="apidocSignatureSpan">svgo.moveElemsAttrsToGroup.</span>description
1.  string <span class="apidocSignatureSpan">svgo.moveElemsAttrsToGroup.</span>type

#### [module svgo.moveGroupAttrsToElems](#apidoc.module.svgo.moveGroupAttrsToElems)
1.  boolean <span class="apidocSignatureSpan">svgo.moveGroupAttrsToElems.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.moveGroupAttrsToElems.</span>fn (item)](#apidoc.element.svgo.moveGroupAttrsToElems.fn)
1.  string <span class="apidocSignatureSpan">svgo.moveGroupAttrsToElems.</span>description
1.  string <span class="apidocSignatureSpan">svgo.moveGroupAttrsToElems.</span>type

#### [module svgo.removeAttrs](#apidoc.module.svgo.removeAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.removeAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeAttrs.</span>fn (item, params)](#apidoc.element.svgo.removeAttrs.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeAttrs.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeAttrs.</span>type

#### [module svgo.removeComments](#apidoc.module.svgo.removeComments)
1.  boolean <span class="apidocSignatureSpan">svgo.removeComments.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeComments.</span>fn (item)](#apidoc.element.svgo.removeComments.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeComments.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeComments.</span>type

#### [module svgo.removeDesc](#apidoc.module.svgo.removeDesc)
1.  boolean <span class="apidocSignatureSpan">svgo.removeDesc.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeDesc.</span>fn (item, params)](#apidoc.element.svgo.removeDesc.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeDesc.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeDesc.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeDesc.</span>type

#### [module svgo.removeDimensions](#apidoc.module.svgo.removeDimensions)
1.  boolean <span class="apidocSignatureSpan">svgo.removeDimensions.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeDimensions.</span>fn (item)](#apidoc.element.svgo.removeDimensions.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeDimensions.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeDimensions.</span>type

#### [module svgo.removeDoctype](#apidoc.module.svgo.removeDoctype)
1.  boolean <span class="apidocSignatureSpan">svgo.removeDoctype.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeDoctype.</span>fn (item)](#apidoc.element.svgo.removeDoctype.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeDoctype.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeDoctype.</span>type

#### [module svgo.removeEditorsNSData](#apidoc.module.svgo.removeEditorsNSData)
1.  boolean <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>fn (item, params)](#apidoc.element.svgo.removeEditorsNSData.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>type

#### [module svgo.removeElementsByAttr](#apidoc.module.svgo.removeElementsByAttr)
1.  boolean <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>fn (item, params)](#apidoc.element.svgo.removeElementsByAttr.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>type

#### [module svgo.removeEmptyAttrs](#apidoc.module.svgo.removeEmptyAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.removeEmptyAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeEmptyAttrs.</span>fn (item)](#apidoc.element.svgo.removeEmptyAttrs.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyAttrs.</span>type

#### [module svgo.removeEmptyContainers](#apidoc.module.svgo.removeEmptyContainers)
1.  boolean <span class="apidocSignatureSpan">svgo.removeEmptyContainers.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeEmptyContainers.</span>fn (item)](#apidoc.element.svgo.removeEmptyContainers.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyContainers.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyContainers.</span>type

#### [module svgo.removeEmptyText](#apidoc.module.svgo.removeEmptyText)
1.  boolean <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>fn (item, params)](#apidoc.element.svgo.removeEmptyText.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>type

#### [module svgo.removeHiddenElems](#apidoc.module.svgo.removeHiddenElems)
1.  boolean <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>fn (item, params)](#apidoc.element.svgo.removeHiddenElems.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>type

#### [module svgo.removeMetadata](#apidoc.module.svgo.removeMetadata)
1.  boolean <span class="apidocSignatureSpan">svgo.removeMetadata.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeMetadata.</span>fn (item)](#apidoc.element.svgo.removeMetadata.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeMetadata.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeMetadata.</span>type

#### [module svgo.removeNonInheritableGroupAttrs](#apidoc.module.svgo.removeNonInheritableGroupAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.removeNonInheritableGroupAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeNonInheritableGroupAttrs.</span>fn (item)](#apidoc.element.svgo.removeNonInheritableGroupAttrs.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeNonInheritableGroupAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeNonInheritableGroupAttrs.</span>type

#### [module svgo.removeRasterImages](#apidoc.module.svgo.removeRasterImages)
1.  boolean <span class="apidocSignatureSpan">svgo.removeRasterImages.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeRasterImages.</span>fn (item)](#apidoc.element.svgo.removeRasterImages.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeRasterImages.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeRasterImages.</span>type

#### [module svgo.removeStyleElement](#apidoc.module.svgo.removeStyleElement)
1.  boolean <span class="apidocSignatureSpan">svgo.removeStyleElement.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeStyleElement.</span>fn (item)](#apidoc.element.svgo.removeStyleElement.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeStyleElement.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeStyleElement.</span>type

#### [module svgo.removeTitle](#apidoc.module.svgo.removeTitle)
1.  boolean <span class="apidocSignatureSpan">svgo.removeTitle.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeTitle.</span>fn (item)](#apidoc.element.svgo.removeTitle.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeTitle.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeTitle.</span>type

#### [module svgo.removeUnknownsAndDefaults](#apidoc.module.svgo.removeUnknownsAndDefaults)
1.  boolean <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>fn (item, params)](#apidoc.element.svgo.removeUnknownsAndDefaults.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>type

#### [module svgo.removeUnusedNS](#apidoc.module.svgo.removeUnusedNS)
1.  boolean <span class="apidocSignatureSpan">svgo.removeUnusedNS.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeUnusedNS.</span>fn (data)](#apidoc.element.svgo.removeUnusedNS.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeUnusedNS.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeUnusedNS.</span>type

#### [module svgo.removeUselessDefs](#apidoc.module.svgo.removeUselessDefs)
1.  boolean <span class="apidocSignatureSpan">svgo.removeUselessDefs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeUselessDefs.</span>fn (item)](#apidoc.element.svgo.removeUselessDefs.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeUselessDefs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeUselessDefs.</span>type

#### [module svgo.removeUselessStrokeAndFill](#apidoc.module.svgo.removeUselessStrokeAndFill)
1.  boolean <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>fn (item, params)](#apidoc.element.svgo.removeUselessStrokeAndFill.fn)
1.  object <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>params
1.  string <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>type

#### [module svgo.removeViewBox](#apidoc.module.svgo.removeViewBox)
1.  boolean <span class="apidocSignatureSpan">svgo.removeViewBox.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeViewBox.</span>fn (item)](#apidoc.element.svgo.removeViewBox.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeViewBox.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeViewBox.</span>type

#### [module svgo.removeXMLNS](#apidoc.module.svgo.removeXMLNS)
1.  boolean <span class="apidocSignatureSpan">svgo.removeXMLNS.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeXMLNS.</span>fn (item)](#apidoc.element.svgo.removeXMLNS.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeXMLNS.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeXMLNS.</span>type

#### [module svgo.removeXMLProcInst](#apidoc.module.svgo.removeXMLProcInst)
1.  boolean <span class="apidocSignatureSpan">svgo.removeXMLProcInst.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.removeXMLProcInst.</span>fn (item)](#apidoc.element.svgo.removeXMLProcInst.fn)
1.  string <span class="apidocSignatureSpan">svgo.removeXMLProcInst.</span>description
1.  string <span class="apidocSignatureSpan">svgo.removeXMLProcInst.</span>type

#### [module svgo.sortAttrs](#apidoc.module.svgo.sortAttrs)
1.  boolean <span class="apidocSignatureSpan">svgo.sortAttrs.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.sortAttrs.</span>fn (item, params)](#apidoc.element.svgo.sortAttrs.fn)
1.  object <span class="apidocSignatureSpan">svgo.sortAttrs.</span>params
1.  string <span class="apidocSignatureSpan">svgo.sortAttrs.</span>description
1.  string <span class="apidocSignatureSpan">svgo.sortAttrs.</span>type

#### [module svgo.transformsWithOnePath](#apidoc.module.svgo.transformsWithOnePath)
1.  boolean <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>active
1.  [function <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>fn (data, params)](#apidoc.element.svgo.transformsWithOnePath.fn)
1.  object <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>params
1.  string <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>description
1.  string <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>type



# <a name="apidoc.module.svgo"></a>[module svgo](#apidoc.module.svgo)



# <a name="apidoc.module.svgo._path"></a>[module svgo._path](#apidoc.module.svgo._path)

#### <a name="apidoc.element.svgo._path.applyTransforms"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>applyTransforms (elem, path, params)](#apidoc.element.svgo._path.applyTransforms)
- description and source-code
```javascript
applyTransforms = function (elem, path, params) {
    // if there are no 'stroke' attr and references to other objects such as
    // gradiends or clip-path which are also subjects to transform.
    if (!elem.hasAttr('transform') || !elem.attr('transform').value ||
        elem.someAttr(function(attr) {
            return ~referencesProps.indexOf(attr.name) && ~attr.value.indexOf('url(');
        }))
        return path;

    var matrix = transformsMultiply(transform2js(elem.attr('transform').value)),
        stroke = elem.computedAttr('stroke'),
        id = elem.computedAttr('id'),
        transformPrecision = params.transformPrecision,
        newPoint, scale;

    if (stroke && stroke != 'none') {
        if (!params.applyTransformsStroked ||
            (matrix.data[0] != matrix.data[3] || matrix.data[1] != -matrix.data[2]) &&
            (matrix.data[0] != -matrix.data[3] || matrix.data[1] != matrix.data[2]))
            return path;

        // "stroke-width" should be inside the part with ID, otherwise it can be overrided in <use>
        if (id) {
            var idElem = elem,
                hasStrokeWidth = false;

            do {
                if (idElem.hasAttr('stroke-width')) hasStrokeWidth = true;
            } while (!idElem.hasAttr('id', id) && !hasStrokeWidth && (idElem = idElem.parentNode));

            if (!hasStrokeWidth) return path;
        }

        scale = +Math.sqrt(matrix.data[0] * matrix.data[0] + matrix.data[1] * matrix.data[1]).toFixed(transformPrecision);

        if (scale !== 1) {
            var strokeWidth = elem.computedAttr('stroke-width') || defaultStrokeWidth;

            if (elem.hasAttr('stroke-width')) {
                elem.attrs['stroke-width'].value = elem.attrs['stroke-width'].value.trim()
                    .replace(regNumericValues, function(num) { return removeLeadingZero(num * scale) });
            } else {
                elem.addAttr({
                    name: 'stroke-width',
                    prefix: '',
                    local: 'stroke-width',
                    value: strokeWidth.replace(regNumericValues, function(num) { return removeLeadingZero(num * scale) })
                });
            }
        }
    } else if (id) { // Stroke and stroke-width can be redefined with <use>
        return path;
    }

    path.forEach(function(pathItem) {

        if (pathItem.data) {

            // h -> l
            if (pathItem.instruction === 'h') {

                pathItem.instruction = 'l';
                pathItem.data[1] = 0;

            // v -> l
            } else if (pathItem.instruction === 'v') {

                pathItem.instruction = 'l';
                pathItem.data[1] = pathItem.data[0];
                pathItem.data[0] = 0;

            }

            // if there is a translate() transform
            if (pathItem.instruction === 'M' &&
                (matrix.data[4] !== 0 ||
                matrix.data[5] !== 0)
            ) {

                // then apply it only to the first absoluted M
                newPoint = transformPoint(matrix.data, pathItem.data[0], pathItem.data[1]);
                set(pathItem.data, newPoint);
                set(pathItem.coords, newPoint);

                // clear translate() data from transform matrix
                matrix.data[4] = 0;
                matrix.data[5] = 0;

            } else {

                if (pathItem.instruction == 'a') {

                    transformArc(pathItem.data, matrix.data);

                    // reduce number of digits in rotation angle
                    if (Math.abs(pathItem.data[2]) > 80) {
                        var a = pathItem.data[0],
                            rotation = pathItem.data[2];
                        pathItem.data[0] = pathItem.data[1];
                        pathItem.data[1] = a;
                        pathItem.data[2] = rotation + (rotation > 0 ? -90 : 90);
                    }

                    newPoint = transformPoint(matrix.data, pathItem.data[5], pathItem.data[6]);
                    pathItem.data[5] = newPoint[0];
                    pathItem.data[6] ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.computeCubicBoundingBox"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>computeCubicBoundingBox (xa, ya, xb, yb, xc, yc, xd, yd)](#apidoc.element.svgo._path.computeCubicBoundingBox)
- description and source-code
```javascript
computeCubicBoundingBox = function (xa, ya, xb, yb, xc, yc, xd, yd) {

    var minx = Number.POSITIVE_INFINITY,
        miny = Number.POSITIVE_INFINITY,
        maxx = Number.NEGATIVE_INFINITY,
        maxy = Number.NEGATIVE_INFINITY,
        ts,
        t,
        x,
        y,
        i;

    // X
    if (xa < minx) { minx = xa; }
    if (xa > maxx) { maxx = xa; }
    if (xd < minx) { minx= xd; }
    if (xd > maxx) { maxx = xd; }

    ts = computeCubicFirstDerivativeRoots(xa, xb, xc, xd);

    for (i = 0; i < ts.length; i++) {

        t = ts[i];

        if (t >= 0 && t <= 1) {
            x = computeCubicBaseValue(t, xa, xb, xc, xd);
            // y = computeCubicBaseValue(t, ya, yb, yc, yd);

            if (x < minx) { minx = x; }
            if (x > maxx) { maxx = x; }
        }

    }

    // Y
    if (ya < miny) { miny = ya; }
    if (ya > maxy) { maxy = ya; }
    if (yd < miny) { miny = yd; }
    if (yd > maxy) { maxy = yd; }

    ts = computeCubicFirstDerivativeRoots(ya, yb, yc, yd);

    for (i = 0; i < ts.length; i++) {

        t = ts[i];

        if (t >= 0 && t <= 1) {
            // x = computeCubicBaseValue(t, xa, xb, xc, xd);
            y = computeCubicBaseValue(t, ya, yb, yc, yd);

            if (y < miny) { miny = y; }
            if (y > maxy) { maxy = y; }
        }

    }

    return {
        minx: minx,
        miny: miny,
        maxx: maxx,
        maxy: maxy
    };

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.computeQuadraticBoundingBox"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>computeQuadraticBoundingBox (xa, ya, xb, yb, xc, yc)](#apidoc.element.svgo._path.computeQuadraticBoundingBox)
- description and source-code
```javascript
computeQuadraticBoundingBox = function (xa, ya, xb, yb, xc, yc) {

    var minx = Number.POSITIVE_INFINITY,
        miny = Number.POSITIVE_INFINITY,
        maxx = Number.NEGATIVE_INFINITY,
        maxy = Number.NEGATIVE_INFINITY,
        t,
        x,
        y;

    // X
    if (xa < minx) { minx = xa; }
    if (xa > maxx) { maxx = xa; }
    if (xc < minx) { minx = xc; }
    if (xc > maxx) { maxx = xc; }

    t = computeQuadraticFirstDerivativeRoot(xa, xb, xc);

    if (t >= 0 && t <= 1) {
        x = computeQuadraticBaseValue(t, xa, xb, xc);
        // y = computeQuadraticBaseValue(t, ya, yb, yc);

        if (x < minx) { minx = x; }
        if (x > maxx) { maxx = x; }
    }

    // Y
    if (ya < miny) { miny = ya; }
    if (ya > maxy) { maxy = ya; }
    if (yc < miny) { miny = yc; }
    if (yc > maxy) { maxy = yc; }

    t = computeQuadraticFirstDerivativeRoot(ya, yb, yc);

    if (t >= 0 && t <=1 ) {
        // x = computeQuadraticBaseValue(t, xa, xb, xc);
        y = computeQuadraticBaseValue(t, ya, yb, yc);

        if (y < miny) { miny = y; }
        if (y > maxy) { maxy = y ; }

    }

    return {
        minx: minx,
        miny: miny,
        maxx: maxx,
        maxy: maxy
    };

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.intersects"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>intersects (path1, path2)](#apidoc.element.svgo._path.intersects)
- description and source-code
```javascript
intersects = function (path1, path2) {
    if (path1.length < 3 || path2.length < 3) return false; // nothing to fill

    // Collect points of every subpath.
    var points1 = relative2absolute(path1).reduce(gatherPoints, []),
        points2 = relative2absolute(path2).reduce(gatherPoints, []);

    // Axis-aligned bounding box check.
    if (points1.maxX <= points2.minX || points2.maxX <= points1.minX ||
        points1.maxY <= points2.minY || points2.maxY <= points1.minY ||
        points1.every(function (set1) {
            return points2.every(function (set2) {
                return set1[set1.maxX][0] <= set2[set2.minX][0] ||
                    set2[set2.maxX][0] <= set1[set1.minX][0] ||
                    set1[set1.maxY][1] <= set2[set2.minY][1] ||
                    set2[set2.maxY][1] <= set1[set1.minY][1];
            });
        })
    ) return false;

    // Get a convex hull from points of each subpath. Has the most complexity O(n·log n).
    var hullNest1 = points1.map(convexHull),
        hullNest2 = points2.map(convexHull);

    // Check intersection of every subpath of the first path with every subpath of the second.
    return hullNest1.some(function(hull1) {
        if (hull1.length < 3) return false;

        return hullNest2.some(function(hull2) {
            if (hull2.length < 3) return false;

            var simplex = [getSupport(hull1, hull2, [1, 0])], // create the initial simplex
                direction = minus(simplex[0]); // set the direction to point towards the origin

            var iterations = 1e4; // infinite loop protection, 10 000 iterations is more than enough
            while (true) {
                if (iterations-- == 0) {
                    console.error('Error: infinite loop while processing mergePaths plugin.');
                    return true; // true is the safe value that means “do nothing with paths”
                }
                // add a new point
                simplex.push(getSupport(hull1, hull2, direction));
                // see if the new point was on the correct side of the origin
                if (dot(direction, simplex[simplex.length - 1]) <= 0) return false;
                // process the simplex
                if (processSimplex(simplex, direction)) return true;
            }
        });
    });

    function getSupport(a, b, direction) {
        return sub(supportPoint(a, direction), supportPoint(b, minus(direction)));
    }

    // Computes farthest polygon point in particular direction.
    // Thanks to knowledge of min/max x and y coordinates we can choose a quadrant to search in.
    // Since we're working on convex hull, the dot product is increasing until we find the farthest point.
    function supportPoint(polygon, direction) {
        var index = direction[1] >= 0 ?
                direction[0] < 0 ? polygon.maxY : polygon.maxX :
                direction[0] < 0 ? polygon.minX : polygon.minY,
            max = -Infinity,
            value;
        while ((value = dot(polygon[index], direction)) > max) {
            max = value;
            index = ++index % polygon.length;
        }
        return polygon[(index || polygon.length) - 1];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.js2path"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>js2path (path, data, params)](#apidoc.element.svgo._path.js2path)
- description and source-code
```javascript
js2path = function (path, data, params) {

    path.pathJS = data;

    if (params.collapseRepeated) {
        data = collapseRepeated(data);
    }

    path.attr('d').value = data.reduce(function(pathString, item) {
        return pathString += item.instruction + (item.data ? cleanupOutData(item.data, params) : '');
    }, '');

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.path2js"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>path2js (path)](#apidoc.element.svgo._path.path2js)
- description and source-code
```javascript
path2js = function (path) {
    if (path.pathJS) return path.pathJS;

    var paramsLength = { // Number of parameters of every path command
            H: 1, V: 1, M: 2, L: 2, T: 2, Q: 4, S: 4, C: 6, A: 7,
            h: 1, v: 1, m: 2, l: 2, t: 2, q: 4, s: 4, c: 6, a: 7
        },
        pathData = [],   // JS representation of the path data
        instruction, // current instruction context
        startMoveto = false;

    // splitting path string into array like ['M', '10 50', 'L', '20 30']
    path.attr('d').value.split(regPathInstructions).forEach(function(data) {
        if (!data) return;
        if (!startMoveto) {
            if (data == 'M' || data == 'm') {
                startMoveto = true;
            } else return;
        }

        // instruction item
        if (regPathInstructions.test(data)) {
            instruction = data;

            // z - instruction w/o data
            if (instruction == 'Z' || instruction == 'z') {
                pathData.push({
                    instruction: 'z'
                });
            }
        // data item
        } else {
            data = data.match(regPathData);
            if (!data) return;

            data = data.map(Number);

            // Subsequent moveto pairs of coordinates are threated as implicit lineto commands
            // http://www.w3.org/TR/SVG/paths.html#PathDataMovetoCommands
            if (instruction == 'M' || instruction == 'm') {
                pathData.push({
                    instruction: pathData.length == 0 ? 'M' : instruction,
                    data: data.splice(0, 2)
                });
                instruction = instruction == 'M' ? 'L' : 'l';
            }

            for (var pair = paramsLength[instruction]; data.length;) {
                pathData.push({
                    instruction: instruction,
                    data: data.splice(0, pair)
                });
            }
        }
    });

    // First moveto is actually absolute. Subsequent coordinates were separated above.
    if (pathData.length && pathData[0].instruction == 'm') {
        pathData[0].instruction = 'M';
    }
    path.pathJS = pathData;

    return pathData;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._path.relative2absolute"></a>[function <span class="apidocSignatureSpan">svgo._path.</span>relative2absolute (data)](#apidoc.element.svgo._path.relative2absolute)
- description and source-code
```javascript
relative2absolute = function (data) {
    var currentPoint = [0, 0],
        subpathPoint = [0, 0],
        i;

    data = data.map(function(item) {

        var instruction = item.instruction,
            itemData = item.data && item.data.slice();

        if (instruction == 'M') {

            set(currentPoint, itemData);
            set(subpathPoint, itemData);

        } else if ('mlcsqt'.indexOf(instruction) > -1) {

            for (i = 0; i < itemData.length; i++) {
                itemData[i] += currentPoint[i % 2];
            }
            set(currentPoint, itemData);

            if (instruction == 'm') {
                set(subpathPoint, itemData);
            }

        } else if (instruction == 'a') {

            itemData[5] += currentPoint[0];
            itemData[6] += currentPoint[1];
            set(currentPoint, itemData);

        } else if (instruction == 'h') {

            itemData[0] += currentPoint[0];
            currentPoint[0] = itemData[0];

        } else if (instruction == 'v') {

            itemData[0] += currentPoint[1];
            currentPoint[1] = itemData[0];

        } else if ('MZLCSQTA'.indexOf(instruction) > -1) {

            set(currentPoint, itemData);

        } else if (instruction == 'H') {

            currentPoint[0] = itemData[0];

        } else if (instruction == 'V') {

            currentPoint[1] = itemData[0];

        } else if (instruction == 'z') {

            set(currentPoint, subpathPoint);

        }

        return instruction == 'z' ?
            { instruction: 'z' } :
            {
                instruction: instruction.toUpperCase(),
                data: itemData
            };

    });

    return data;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo._transforms"></a>[module svgo._transforms](#apidoc.module.svgo._transforms)

#### <a name="apidoc.element.svgo._transforms.matrixToTransform"></a>[function <span class="apidocSignatureSpan">svgo._transforms.</span>matrixToTransform (transform, params)](#apidoc.element.svgo._transforms.matrixToTransform)
- description and source-code
```javascript
matrixToTransform = function (transform, params) {
    var floatPrecision = params.floatPrecision,
        data = transform.data,
        transforms = [],
        sx = +Math.sqrt(data[0] * data[0] + data[1] * data[1]).toFixed(params.transformPrecision),
        sy = +((data[0] * data[3] - data[1] * data[2]) / sx).toFixed(params.transformPrecision),
        colsSum = data[0] * data[2] + data[1] * data[3],
        rowsSum = data[0] * data[1] + data[2] * data[3],
        scaleBefore = rowsSum || +(sx == sy);

    // [..., ..., ..., ..., tx, ty] → translate(tx, ty)
    if (data[4] || data[5]) {
        transforms.push({ name: 'translate', data: data.slice(4, data[5] ? 6 : 5) });
    }

    // [sx, 0, tan(a)·sy, sy, 0, 0] → skewX(a)·scale(sx, sy)
    if (!data[1] && data[2]) {
        transforms.push({ name: 'skewX', data: [mth.atan(data[2] / sy, floatPrecision)] });

    // [sx, sx·tan(a), 0, sy, 0, 0] → skewY(a)·scale(sx, sy)
    } else if (data[1] && !data[2]) {
        transforms.push({ name: 'skewY', data: [mth.atan(data[1] / data[0], floatPrecision)] });
        sx = data[0];
        sy = data[3];

    // [sx·cos(a), sx·sin(a), sy·-sin(a), sy·cos(a), x, y] → rotate(a[, cx, cy])·(scale or skewX) or
    // [sx·cos(a), sy·sin(a), sx·-sin(a), sy·cos(a), x, y] → scale(sx, sy)·rotate(a[, cx, cy]) (if !scaleBefore)
    } else if (!colsSum || (sx == 1 && sy == 1) || !scaleBefore) {
        if (!scaleBefore) {
            sx = (data[0] < 0 ? -1 : 1) * Math.sqrt(data[0] * data[0] + data[2] * data[2]);
            sy = (data[3] < 0 ? -1 : 1) * Math.sqrt(data[1] * data[1] + data[3] * data[3]);
            transforms.push({ name: 'scale', data: [sx, sy] });
        }
        var rotate = [mth.acos(data[0] / sx, floatPrecision) * (data[1] * sy < 0 ? -1 : 1)];

        if (rotate[0]) transforms.push({ name: 'rotate', data: rotate });

        if (rowsSum && colsSum) transforms.push({
            name: 'skewX',
            data: [mth.atan(colsSum / (sx * sx), floatPrecision)]
        });

        // rotate(a, cx, cy) can consume translate() within optional arguments cx, cy (rotation point)
        if (rotate[0] && (data[4] || data[5])) {
            transforms.shift();
            var cos = data[0] / sx,
                sin = data[1] / (scaleBefore ? sx : sy),
                x = data[4] * (scaleBefore || sy),
                y = data[5] * (scaleBefore || sx),
                denom = (Math.pow(1 - cos, 2) + Math.pow(sin, 2)) * (scaleBefore || sx * sy);
            rotate.push(((1 - cos) * x - sin * y) / denom);
            rotate.push(((1 - cos) * y + sin * x) / denom);
        }

    // Too many transformations, return original matrix if it isn't just a scale/translate
    } else if (data[1] || data[2]) {
        return transform;
    }

    if (scaleBefore && (sx != 1 || sy != 1) || !transforms.length) transforms.push({
        name: 'scale',
        data: sx == sy ? [sx] : [sx, sy]
    });

    return transforms;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._transforms.transform2js"></a>[function <span class="apidocSignatureSpan">svgo._transforms.</span>transform2js (transformString)](#apidoc.element.svgo._transforms.transform2js)
- description and source-code
```javascript
transform2js = function (transformString) {

        // JS representation of the transform data
    var transforms = [],
        // current transform context
        current;

    // split value into ['', 'translate', '10 50', '', 'scale', '2', '', 'rotate', '-45', '']
    transformString.split(regTransformSplit).forEach(function(item) {
<span class="apidocCodeCommentSpan">        /*jshint -W084 */
</span>        var num;

        if (item) {
            // if item is a translate function
            if (regTransformTypes.test(item)) {
                // then collect it and change current context
                transforms.push(current = { name: item });
            // else if item is data
            } else {
                // then split it into [10, 50] and collect as context.data
                while (num = regNumericValues.exec(item)) {
                    num = Number(num);
                    if (current.data)
                        current.data.push(num);
                    else
                        current.data = [num];
                }
            }
        }
    });

    return transforms;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._transforms.transformArc"></a>[function <span class="apidocSignatureSpan">svgo._transforms.</span>transformArc (arc, transform)](#apidoc.element.svgo._transforms.transformArc)
- description and source-code
```javascript
transformArc = function (arc, transform) {

    var a = arc[0],
        b = arc[1],
        rot = arc[2] * Math.PI / 180,
        cos = Math.cos(rot),
        sin = Math.sin(rot),
        h = Math.pow(arc[5] * cos + arc[6] * sin, 2) / (4 * a * a) +
            Math.pow(arc[6] * cos - arc[5] * sin, 2) / (4 * b * b);
    if (h > 1) {
        h = Math.sqrt(h);
        a *= h;
        b *= h;
    }
    var ellipse = [a * cos, a * sin, -b * sin, b * cos, 0, 0],
        m = multiplyTransformMatrices(transform, ellipse),
        // Decompose the new ellipse matrix
        lastCol = m[2] * m[2] + m[3] * m[3],
        squareSum = m[0] * m[0] + m[1] * m[1] + lastCol,
        root = Math.sqrt(
            (Math.pow(m[0] - m[3], 2) + Math.pow(m[1] + m[2], 2)) *
            (Math.pow(m[0] + m[3], 2) + Math.pow(m[1] - m[2], 2))
        );

    if (!root) { // circle
        arc[0] = arc[1] = Math.sqrt(squareSum / 2);
        arc[2] = 0;
    } else {
        var majorAxisSqr = (squareSum + root) / 2,
            minorAxisSqr = (squareSum - root) / 2,
            major = Math.abs(majorAxisSqr - lastCol) > 1e-6,
            sub = (major ? majorAxisSqr : minorAxisSqr) - lastCol,
            rowsSum = m[0] * m[2] + m[1] * m[3],
            term1 = m[0] * sub + m[2] * rowsSum,
            term2 = m[1] * sub + m[3] * rowsSum;
        arc[0] = Math.sqrt(majorAxisSqr);
        arc[1] = Math.sqrt(minorAxisSqr);
        arc[2] = ((major ? term2 < 0 : term1 > 0) ? -1 : 1) *
            Math.acos((major ? term1 : term2) / Math.sqrt(term1 * term1 + term2 * term2)) * 180 / Math.PI;
    }
    return arc;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.svgo._transforms.transformsMultiply"></a>[function <span class="apidocSignatureSpan">svgo._transforms.</span>transformsMultiply (transforms)](#apidoc.element.svgo._transforms.transformsMultiply)
- description and source-code
```javascript
transformsMultiply = function (transforms) {

    // convert transforms objects to the matrices
    transforms = transforms.map(function(transform) {
        if (transform.name === 'matrix') {
            return transform.data;
        }
        return transformToMatrix(transform);
    });

    // multiply all matrices into one
    transforms = {
        name: 'matrix',
        data: transforms.reduce(function(a, b) {
            return multiplyTransformMatrices(a, b);
        })
    };

    return transforms;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.addAttributesToSVGElement"></a>[module svgo.addAttributesToSVGElement](#apidoc.module.svgo.addAttributesToSVGElement)

#### <a name="apidoc.element.svgo.addAttributesToSVGElement.fn"></a>[function <span class="apidocSignatureSpan">svgo.addAttributesToSVGElement.</span>fn (data, params)](#apidoc.element.svgo.addAttributesToSVGElement.fn)
- description and source-code
```javascript
fn = function (data, params) {
    if (!params || !(Array.isArray(params.attributes) && params.attributes.some(String) || params.attribute)) {
        console.error(ENOCLS);
        return data;
    }

    var attributes = params.attributes || [ params.attribute ],
        svg = data.content[0];

    if (svg.isElem('svg')) {
        attributes.forEach(function (attribute) {
            if (!svg.hasAttr(attribute)) {
                svg.addAttr({
                    name: attribute,
                    prefix: '',
                    local: attribute
                });
            }
        });
    }

    return data;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.addClassesToSVGElement"></a>[module svgo.addClassesToSVGElement](#apidoc.module.svgo.addClassesToSVGElement)

#### <a name="apidoc.element.svgo.addClassesToSVGElement.fn"></a>[function <span class="apidocSignatureSpan">svgo.addClassesToSVGElement.</span>fn (data, params)](#apidoc.element.svgo.addClassesToSVGElement.fn)
- description and source-code
```javascript
fn = function (data, params) {
    if (!params || !(Array.isArray(params.classNames) && params.classNames.some(String) || params.className)) {
        console.error(ENOCLS);
        return data;
    }

    var classNames = params.classNames || [ params.className ],
        svg = data.content[0];

    if (svg.isElem('svg')) {
        if (svg.hasAttr('class')) {
            var classes = svg.attr('class').value.split(' ');
            classNames.forEach(function(className){
                if (classes.indexOf(className) < 0) {
                    classes.push(className);
                }
            });
            svg.attr('class').value = classes.join(' ');
        } else {
            svg.addAttr({
                name: 'class',
                value: classNames.join(' '),
                prefix: '',
                local: 'class'
            });
        }
    }

    return data;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.cleanupAttrs"></a>[module svgo.cleanupAttrs](#apidoc.module.svgo.cleanupAttrs)

#### <a name="apidoc.element.svgo.cleanupAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.cleanupAttrs.</span>fn (item, params)](#apidoc.element.svgo.cleanupAttrs.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.isElem()) {

        item.eachAttr(function(attr) {

            if (params.newlines) {
                // new line which requires a space instead of themselve
                attr.value = attr.value.replace(regNewlinesNeedSpace, function(match, p1, p2) {
                    return p1 + ' ' + p2;
                });

                // simple new line
                attr.value = attr.value.replace(regNewlines, '');
            }

            if (params.trim) {
                attr.value = attr.value.trim();
            }

            if (params.spaces) {
                attr.value = attr.value.replace(regSpaces, ' ');
            }

        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.cleanupEnableBackground"></a>[module svgo.cleanupEnableBackground](#apidoc.module.svgo.cleanupEnableBackground)

#### <a name="apidoc.element.svgo.cleanupEnableBackground.fn"></a>[function <span class="apidocSignatureSpan">svgo.cleanupEnableBackground.</span>fn (data)](#apidoc.element.svgo.cleanupEnableBackground.fn)
- description and source-code
```javascript
fn = function (data) {

    var regEnableBackground = /^new\s0\s0\s([\-+]?\d*\.?\d+([eE][\-+]?\d+)?)\s([\-+]?\d*\.?\d+([eE][\-+]?\d+)?)$/,
        hasFilter = false,
        elems = ['svg', 'mask', 'pattern'];

    function checkEnableBackground(item) {
        if (
            item.isElem(elems) &&
            item.hasAttr('enable-background') &&
            item.hasAttr('width') &&
            item.hasAttr('height')
        ) {

            var match = item.attr('enable-background').value.match(regEnableBackground);

            if (match) {
                if (
                    item.attr('width').value === match[1] &&
                    item.attr('height').value === match[3]
                ) {
                    if (item.isElem('svg')) {
                        item.removeAttr('enable-background');
                    } else {
                        item.attr('enable-background').value = 'new';
                    }
                }
            }

        }
    }

    function checkForFilter(item) {
        if (item.isElem('filter')) {
            hasFilter = true;
        }
    }

    function monkeys(items, fn) {
        items.content.forEach(function(item) {
            fn(item);

            if (item.content) {
                monkeys(item, fn);
            }
        });
        return items;
    }

    var firstStep = monkeys(data, function(item) {
        checkEnableBackground(item);
        if (!hasFilter) {
            checkForFilter(item);
        }
    });

    return hasFilter ? firstStep : monkeys(firstStep, function(item) {
            //we don't need 'enable-background' if we have no filters
            item.removeAttr('enable-background');
        });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.cleanupIDs"></a>[module svgo.cleanupIDs](#apidoc.module.svgo.cleanupIDs)

#### <a name="apidoc.element.svgo.cleanupIDs.fn"></a>[function <span class="apidocSignatureSpan">svgo.cleanupIDs.</span>fn (data, params)](#apidoc.element.svgo.cleanupIDs.fn)
- description and source-code
```javascript
fn = function (data, params) {

    var currentID,
        currentIDstring,
        IDs = Object.create(null),
        referencesIDs = Object.create(null),
        idPrefix = 'id-', // prefix IDs so that values like '__proto__' don't break the work
        hasStyleOrScript = false;

<span class="apidocCodeCommentSpan">    /**
     * Bananas!
     *
     * @param {Array} items input items
     * @return {Array} output items
     */
</span>    function monkeys(items) {

        for (var i = 0; i < items.content.length && !hasStyleOrScript; i++) {

            var item = items.content[i],
                match;

            // check if <style> of <script> presents
            if (item.isElem(styleOrScript)) {
                hasStyleOrScript = true;
                continue;
            }

            // …and don't remove any ID if yes
            if (item.isElem()) {

                item.eachAttr(function(attr) {
                    var key;
                    // save IDs
                    if (attr.name === 'id') {
                        key = idPrefix + attr.value;
                        if (key in IDs) {
                            item.removeAttr('id');
                        } else {
                            IDs[key] = item;
                        }
                    }

                    // save IDs url() references
                    else if (referencesProps.indexOf(attr.name) > -1) {
                        match = attr.value.match(regReferencesUrl);

                        if (match) {
                            key = idPrefix + match[2];
                            if (referencesIDs[key]) {
                                referencesIDs[key].push(attr);
                            } else {
                                referencesIDs[key] = [attr];
                            }
                        }
                    }

                    // save IDs href references
                    else if (
                        attr.local === 'href' && (match = attr.value.match(regReferencesHref)) ||
                        attr.name === 'begin' && (match = attr.value.match(regReferencesBegin))
                    ) {
                        key = idPrefix + match[1];
                        if (referencesIDs[key]) {
                            referencesIDs[key].push(attr);
                        } else {
                            referencesIDs[key] = [attr];
                        }
                    }
                });

            }

            // go deeper
            if (item.content) {
                monkeys(item);
            }
        }

        return items;

    }

    data = monkeys(data);

    if (hasStyleOrScript) {
        return data;
    }

    var idKey;
    for (var k in referencesIDs) {
        if (IDs[k]) {
            idKey = k;
            k = k.replace(idPrefix, '');
            // replace referenced IDs with the minified ones
            if (params.minify) {
                currentIDstring = getIDstring(currentID = generateID(currentID), params);
                IDs[idKey].attr('id').value = currentIDstring;

                referencesIDs[idKey].forEach(function(attr) {
                    attr.value = attr.value
                        .replace('#' + k, '#' + currentIDstring)
                        .replace(k + '.', currentIDstring + '.');
                });

                idKey = idPrefix + k;
            }

            // don't remove referenced IDs
            delete IDs[idKey];
        }
    }

    // remove non-referenced IDs attributes from elements
    if (params.remove) {

        for(var ID in IDs) {
            IDs[ID].removeAttr('id');
        }

    }

    return data;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.cleanupListOfValues"></a>[module svgo.cleanupListOfValues](#apidoc.module.svgo.cleanupListOfValues)

#### <a name="apidoc.element.svgo.cleanupListOfValues.fn"></a>[function <span class="apidocSignatureSpan">svgo.cleanupListOfValues.</span>fn (item, params)](#apidoc.element.svgo.cleanupListOfValues.fn)
- description and source-code
```javascript
fn = function (item, params) {


    if ( item.hasAttr('points') ) {
        roundValues(item.attrs.points);
    }

    if ( item.hasAttr('enable-background') ) {
        roundValues(item.attrs['enable-background']);
    }

    if ( item.hasAttr('viewBox') ) {
        roundValues(item.attrs.viewBox);
    }

    if ( item.hasAttr('stroke-dasharray') ) {
        roundValues(item.attrs['stroke-dasharray']);
    }

    if ( item.hasAttr('dx') ) {
        roundValues(item.attrs.dx);
    }

    if ( item.hasAttr('dy') ) {
        roundValues(item.attrs.dy);
    }

    if ( item.hasAttr('x') ) {
        roundValues(item.attrs.x);
    }

    if ( item.hasAttr('y') ) {
        roundValues(item.attrs.y);
    }


    function roundValues($prop){

        var num, units,
            match,
            matchNew,
            lists = $prop.value,
            listsArr = lists.split(regSeparator),
            roundedListArr = [],
            roundedList;

        listsArr.forEach(function(elem){

            match = elem.match(regNumericValues);
            matchNew = elem.match(/new/);

             // if attribute value matches regNumericValues
            if(match){

                // round it to the fixed precision
                num = +(+match[1]).toFixed(params.floatPrecision),
                units = match[3] || '';

                // convert absolute values to pixels
                if (params.convertToPx && units && (units in absoluteLengths)) {
                    var pxNum = +(absoluteLengths[units] * match[1]).toFixed(params.floatPrecision);

                    if (String(pxNum).length < match[0].length)
                        num = pxNum,
                        units = 'px';
                }

                 // and remove leading zero
                if (params.leadingZero) {
                    num = removeLeadingZero(num);
                }

                // remove default 'px' units
                if (params.defaultPx && units === 'px') {
                    units = '';
                }

                roundedListArr.push(num+units);

            }
            // if attribute value is "new"(only enable-background).
            else if(matchNew){

                roundedListArr.push('new');

            }

        });

        roundedList = roundedListArr.join(' ');
        $prop.value = roundedList;

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.cleanupNumericValues"></a>[module svgo.cleanupNumericValues](#apidoc.module.svgo.cleanupNumericValues)

#### <a name="apidoc.element.svgo.cleanupNumericValues.fn"></a>[function <span class="apidocSignatureSpan">svgo.cleanupNumericValues.</span>fn (item, params)](#apidoc.element.svgo.cleanupNumericValues.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.isElem()) {

        var match;

        item.eachAttr(function(attr) {
            match = attr.value.match(regNumericValues);

            // if attribute value matches regNumericValues
            if (match) {
                // round it to the fixed precision
                var num = +(+match[1]).toFixed(params.floatPrecision),
                    units = match[3] || '';

                // convert absolute values to pixels
                if (params.convertToPx && units && (units in absoluteLengths)) {
                    var pxNum = +(absoluteLengths[units] * match[1]).toFixed(params.floatPrecision);

                    if (String(pxNum).length < match[0].length)
                        num = pxNum,
                        units = 'px';
                }

                // and remove leading zero
                if (params.leadingZero) {
                    num = removeLeadingZero(num);
                }

                // remove default 'px' units
                if (params.defaultPx && units === 'px') {
                    units = '';
                }

                attr.value = num + units;
            }
        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.collapseGroups"></a>[module svgo.collapseGroups](#apidoc.module.svgo.collapseGroups)

#### <a name="apidoc.element.svgo.collapseGroups.fn"></a>[function <span class="apidocSignatureSpan">svgo.collapseGroups.</span>fn (item)](#apidoc.element.svgo.collapseGroups.fn)
- description and source-code
```javascript
fn = function (item) {

    // non-empty elements
    if (item.isElem() && !item.isElem('switch') && !item.isEmpty()) {

        item.content.forEach(function(g, i) {

            // non-empty groups
            if (g.isElem('g') && !g.isEmpty()) {

                // move group attibutes to the single content element
                if (g.hasAttr() && g.content.length === 1) {
                    var inner = g.content[0];

                    if (inner.isElem() && !inner.hasAttr('id') &&
                        !(g.hasAttr('class') && inner.hasAttr('class')) && (
                            !g.hasAttr('clip-path') && !g.hasAttr('mask') ||
                            inner.isElem('g') && !g.hasAttr('transform') && !inner.hasAttr('transform')
                        )
                    ) {
                        g.eachAttr(function(attr) {
                            if (g.content.some(hasAnimatedAttr, attr.name)) return;

                            if (!inner.hasAttr(attr.name)) {
                                inner.addAttr(attr);
                            } else if (attr.name == 'transform') {
                                inner.attr(attr.name).value = attr.value + ' ' + inner.attr(attr.name).value;
                            } else if (
                                attrsInheritable.indexOf(attr.name) < 0 &&
                                !inner.hasAttr(attr.name, attr.value)
                            ) {
                                return;
                            }

                            g.removeAttr(attr.name);
                        });
                    }
                }

                // collapse groups without attributes
                if (!g.hasAttr() && !g.content.some(function(item) { return item.isElem(animationElems) })) {
                    item.spliceContent(i, 1, g.content);
                }
            }

        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.convertColors"></a>[module svgo.convertColors](#apidoc.module.svgo.convertColors)

#### <a name="apidoc.element.svgo.convertColors.fn"></a>[function <span class="apidocSignatureSpan">svgo.convertColors.</span>fn (item, params)](#apidoc.element.svgo.convertColors.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.elem) {

        item.eachAttr(function(attr) {

            if (collections.colorsProps.indexOf(attr.name) > -1) {

                var val = attr.value,
                    match;

                // Convert colors to currentColor
                if (params.currentColor) {
                    if (typeof params.currentColor === 'string') {
                        match = val === params.currentColor;
                    } else if (params.currentColor.exec) {
                        match = params.currentColor.exec(val);
                    } else {
                        match = !val.match(none);
                    }
                    if (match) {
                        val = 'currentColor';
                    }
                }

                // Convert color name keyword to long hex
                if (params.names2hex && val.toLowerCase() in collections.colorsNames) {
                    val = collections.colorsNames[val.toLowerCase()];
                }

                // Convert rgb() to long hex
                if (params.rgb2hex && (match = val.match(regRGB))) {
                    match = match.slice(1, 4).map(function(m) {
                        if (m.indexOf('%') > -1)
                            m = Math.round(parseFloat(m) * 2.55);

                        return Math.max(0, Math.min(m, 255));
                    });

                    val = rgb2hex(match);
                }

                // Convert long hex to short hex
                if (params.shorthex && (match = val.match(regHEX))) {
                    val = '#' + match[0][1] + match[0][3] + match[0][5];
                }

                // Convert hex to short name
                if (params.shortname && val in collections.colorsShortNames) {
                    val = collections.colorsShortNames[val];
                }

                attr.value = val;

            }

        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.convertPathData"></a>[module svgo.convertPathData](#apidoc.module.svgo.convertPathData)

#### <a name="apidoc.element.svgo.convertPathData.fn"></a>[function <span class="apidocSignatureSpan">svgo.convertPathData.</span>fn (item, params)](#apidoc.element.svgo.convertPathData.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.isElem(pathElems) && item.hasAttr('d')) {

        precision = params.floatPrecision;
        error = precision !== false ? +Math.pow(.1, precision).toFixed(precision) : 1e-2;
        roundData = precision > 0 && precision < 20 ? strongRound : round;
        if (params.makeArcs) {
            arcThreshold = params.makeArcs.threshold;
            arcTolerance = params.makeArcs.tolerance;
        }
        hasMarkerMid = item.hasAttr('marker-mid');

        var data = path2js(item);

        // TODO: get rid of functions returns
        if (data.length) {
            convertToRelative(data);

            if (params.applyTransforms) {
                data = applyTransforms(item, data, params);
            }

            data = filters(data, params);

            if (params.utilizeAbsolute) {
                data = convertToMixed(data, params);
            }

            js2path(item, data, params);
        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.convertShapeToPath"></a>[module svgo.convertShapeToPath](#apidoc.module.svgo.convertShapeToPath)

#### <a name="apidoc.element.svgo.convertShapeToPath.fn"></a>[function <span class="apidocSignatureSpan">svgo.convertShapeToPath.</span>fn (item)](#apidoc.element.svgo.convertShapeToPath.fn)
- description and source-code
```javascript
fn = function (item) {

    if (
        item.isElem('rect') &&
        item.hasAttr('width') &&
        item.hasAttr('height') &&
        !item.hasAttr('rx') &&
        !item.hasAttr('ry')
    ) {

        var x = +(item.attr('x') || none).value,
            y = +(item.attr('y') || none).value,
            width  = +item.attr('width').value,
            height = +item.attr('height').value;

            // Values like '100%' compute to NaN, thus running after
            // cleanupNumericValues when 'px' units has already been removed.
            // TODO: Calculate sizes from % and non-px units if possible.
        if (isNaN(x - y + width - height)) return;

        var pathData =
            'M' + x + ' ' + y +
            'H' + (x + width) +
            'V' + (y + height) +
            'H' + x +
            'z';

        item.addAttr({
                name: 'd',
                value: pathData,
                prefix: '',
                local: 'd'
            });

        item.renameElem('path')
            .removeAttr(['x', 'y', 'width', 'height']);

    } else if (item.isElem('line')) {

        var x1 = +(item.attr('x1') || none).value,
            y1 = +(item.attr('y1') || none).value,
            x2 = +(item.attr('x2') || none).value,
            y2 = +(item.attr('y2') || none).value;
        if (isNaN(x1 - y1 + x2 - y2)) return;

        item.addAttr({
                name: 'd',
                value: 'M' + x1 + ' ' + y1 + 'L' + x2 + ' ' + y2,
                prefix: '',
                local: 'd'
            });

        item.renameElem('path')
            .removeAttr(['x1', 'y1', 'x2', 'y2']);

    } else if ((
            item.isElem('polyline') ||
            item.isElem('polygon')
        ) &&
        item.hasAttr('points')
    ) {

        var coords = (item.attr('points').value.match(regNumber) || []).map(Number);
        if (coords.length < 4) return false;

        item.addAttr({
                name: 'd',
                value: 'M' + coords.slice(0,2).join(' ') +
                       'L' + coords.slice(2).join(' ') +
                       (item.isElem('polygon') ? 'z' : ''),
                prefix: '',
                local: 'd'
            });

        item.renameElem('path')
            .removeAttr('points');
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.convertStyleToAttrs"></a>[module svgo.convertStyleToAttrs](#apidoc.module.svgo.convertStyleToAttrs)

#### <a name="apidoc.element.svgo.convertStyleToAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.convertStyleToAttrs.</span>fn (item)](#apidoc.element.svgo.convertStyleToAttrs.fn)
- description and source-code
```javascript
fn = function (item) {
<span class="apidocCodeCommentSpan">    /* jshint boss: true */
</span>
    if (item.elem && item.hasAttr('style')) {
            // ['opacity: 1', 'color: #000']
        var styleValue = item.attr('style').value,
            styles = [],
            attrs = {};

        // Strip CSS comments preserving escape sequences and strings.
        styleValue = styleValue.replace(regStripComments, function(match) {
            return match[0] == '/' ? '' :
                match[0] == '\\' && /[-g-z]/i.test(match[1]) ? match[1] : match;
        });

        regDeclarationBlock.lastIndex = 0;
        for (var rule; rule = regDeclarationBlock.exec(styleValue);) {
            styles.push([rule[1], rule[2]]);
        }

        if (styles.length) {

            styles = styles.filter(function(style) {
                if (style[0]) {
                    var prop = style[0].toLowerCase(),
                        val = style[1];

                    if (rQuotedString.test(val)) {
                        val = val.slice(1, -1);
                    }

                    if (stylingProps.indexOf(prop) > -1) {

                        attrs[prop] = {
                            name: prop,
                            value: val,
                            local: prop,
                            prefix: ''
                        };

                        return false;
                    }
                }

                return true;
            });

            EXTEND(item.attrs, attrs);

            if (styles.length) {
                item.attr('style').value = styles
                    .map(function(declaration) { return declaration.join(':') })
                    .join(';');
            } else {
                item.removeAttr('style');
            }

        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.convertTransform"></a>[module svgo.convertTransform](#apidoc.module.svgo.convertTransform)

#### <a name="apidoc.element.svgo.convertTransform.fn"></a>[function <span class="apidocSignatureSpan">svgo.convertTransform.</span>fn (item, params)](#apidoc.element.svgo.convertTransform.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.elem) {

        // transform
        if (item.hasAttr('transform')) {
            convertTransform(item, 'transform', params);
        }

        // gradientTransform
        if (item.hasAttr('gradientTransform')) {
            convertTransform(item, 'gradientTransform', params);
        }

        // patternTransform
        if (item.hasAttr('patternTransform')) {
            convertTransform(item, 'patternTransform', params);
        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.mergePaths"></a>[module svgo.mergePaths](#apidoc.module.svgo.mergePaths)

#### <a name="apidoc.element.svgo.mergePaths.fn"></a>[function <span class="apidocSignatureSpan">svgo.mergePaths.</span>fn (item, params)](#apidoc.element.svgo.mergePaths.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (!item.isElem() || item.isEmpty()) return;

    var prevContentItem = null,
        prevContentItemKeys = null;

    item.content = item.content.filter(function(contentItem) {

        if (prevContentItem &&
            prevContentItem.isElem('path') &&
            prevContentItem.isEmpty() &&
            prevContentItem.hasAttr('d') &&
            contentItem.isElem('path') &&
            contentItem.isEmpty() &&
            contentItem.hasAttr('d')
        ) {

            if (!prevContentItemKeys) {
                prevContentItemKeys = Object.keys(prevContentItem.attrs);
            }

            var contentItemAttrs = Object.keys(contentItem.attrs),
                equalData = prevContentItemKeys.length == contentItemAttrs.length &&
                    contentItemAttrs.every(function(key) {
                        return key == 'd' ||
                            prevContentItem.hasAttr(key) &&
                            prevContentItem.attr(key).value == contentItem.attr(key).value;
                    }),
                prevPathJS = path2js(prevContentItem),
                curPathJS = path2js(contentItem);

            if (equalData && !intersects(prevPathJS, curPathJS)) {
                js2path(prevContentItem, prevPathJS.concat(curPathJS), params);
                return false;
            }
        }

        prevContentItem = contentItem;
        prevContentItemKeys = null;
        return true;

    });

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.minifyStyles"></a>[module svgo.minifyStyles](#apidoc.module.svgo.minifyStyles)

#### <a name="apidoc.element.svgo.minifyStyles.fn"></a>[function <span class="apidocSignatureSpan">svgo.minifyStyles.</span>fn (item, svgoOptions)](#apidoc.element.svgo.minifyStyles.fn)
- description and source-code
```javascript
fn = function (item, svgoOptions) {

    if(item.elem) {
        if(item.isElem('style') && !item.isEmpty()) {
            var styleCss = item.content[0].text || item.content[0].cdata || [],
                DATA = styleCss.indexOf('>') >= 0 || styleCss.indexOf('<') >= 0 ? 'cdata' : 'text';
            if(styleCss.length > 0) {
                var styleCssMinified = csso.minify(styleCss, svgoOptions);
                item.content[0][DATA] = styleCssMinified.css;
            }
      }

      if(item.hasAttr('style')) {
          var itemCss = item.attr('style').value;
          if(itemCss.length > 0) {
              var itemCssMinified = csso.minifyBlock(itemCss, svgoOptions);
              item.attr('style').value = itemCssMinified.css;
          }
      }
    }

    return item;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.moveElemsAttrsToGroup"></a>[module svgo.moveElemsAttrsToGroup](#apidoc.module.svgo.moveElemsAttrsToGroup)

#### <a name="apidoc.element.svgo.moveElemsAttrsToGroup.fn"></a>[function <span class="apidocSignatureSpan">svgo.moveElemsAttrsToGroup.</span>fn (item)](#apidoc.element.svgo.moveElemsAttrsToGroup.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.isElem('g') && !item.isEmpty() && item.content.length > 1) {

        var intersection = {},
            hasTransform = false,
            hasClip = item.hasAttr('clip-path') || item.hasAttr('mask'),
            intersected = item.content.every(function(inner) {
                if (inner.isElem() && inner.hasAttr()) {
                    // don't mess with possible styles (hack until CSS parsing is implemented)
                    if (inner.hasAttr('class')) return false;
                    if (!Object.keys(intersection).length) {
                        intersection = inner.attrs;
                    } else {
                        intersection = intersectInheritableAttrs(intersection, inner.attrs);

                        if (!intersection) return false;
                    }

                    return true;
                }
            }),
            allPath = item.content.every(function(inner) {
                return inner.isElem(pathElems);
            });

        if (intersected) {

            item.content.forEach(function(g) {

                for (var name in intersection) {

                    if (!allPath && !hasClip || name !== 'transform') {

                        g.removeAttr(name);

                        if (name === 'transform') {
                            if (!hasTransform) {
                                if (item.hasAttr('transform')) {
                                    item.attr('transform').value += ' ' + intersection[name].value;
                                } else {
                                    item.addAttr(intersection[name]);
                                }

                                hasTransform = true;
                            }
                        } else {
                            item.addAttr(intersection[name]);
                        }

                    }
                }

            });

        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.moveGroupAttrsToElems"></a>[module svgo.moveGroupAttrsToElems](#apidoc.module.svgo.moveGroupAttrsToElems)

#### <a name="apidoc.element.svgo.moveGroupAttrsToElems.fn"></a>[function <span class="apidocSignatureSpan">svgo.moveGroupAttrsToElems.</span>fn (item)](#apidoc.element.svgo.moveGroupAttrsToElems.fn)
- description and source-code
```javascript
fn = function (item) {

    // move group transform attr to content's pathElems
    if (
        item.isElem('g') &&
        item.hasAttr('transform') &&
        !item.isEmpty() &&
        !item.someAttr(function(attr) {
            return ~referencesProps.indexOf(attr.name) && ~attr.value.indexOf('url(');
        }) &&
        item.content.every(function(inner) {
            return inner.isElem(pathElems) && !inner.hasAttr('id');
        })
    ) {
        item.content.forEach(function(inner) {
            var attr = item.attr('transform');
            if (inner.hasAttr('transform')) {
                inner.attr('transform').value = attr.value + ' ' + inner.attr('transform').value;
            } else {
                inner.addAttr({
                    'name': attr.name,
                    'local': attr.local,
                    'prefix': attr.prefix,
                    'value': attr.value
                });
            }
        });

        item.removeAttr('transform');
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeAttrs"></a>[module svgo.removeAttrs](#apidoc.module.svgo.removeAttrs)

#### <a name="apidoc.element.svgo.removeAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeAttrs.</span>fn (item, params)](#apidoc.element.svgo.removeAttrs.fn)
- description and source-code
```javascript
fn = function (item, params) {

        // wrap into an array if params is not
    if (!Array.isArray(params.attrs)) {
        params.attrs = [params.attrs];
    }

    if (item.isElem()) {

            // prepare patterns
        var patterns = params.attrs.map(function(pattern) {

                // apply to all elements if specifc element is omitted
            if (pattern.indexOf(ELEM_SEP) === -1) {
                pattern = ['.*', ELEM_SEP, pattern].join('');
            }

                // create regexps for element and attribute name
            return pattern.split(ELEM_SEP)
                .map(function(value) {

                        // adjust single * to match anything
                    if (value === '*') { value = '.*'; }

                    return new RegExp(['^', value, '$'].join(''), 'i');
                });

        });

            // loop patterns
        patterns.forEach(function(pattern) {

                // matches element
            if (pattern[0].test(item.elem)) {

                    // loop attributes
                item.eachAttr(function(attr) {
                    var name = attr.name;

                        // matches attribute name
                    if (pattern[1].test(name)) {
                        item.removeAttr(name);
                    }

                });

            }

        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeComments"></a>[module svgo.removeComments](#apidoc.module.svgo.removeComments)

#### <a name="apidoc.element.svgo.removeComments.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeComments.</span>fn (item)](#apidoc.element.svgo.removeComments.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.comment && item.comment.charAt(0) !== '!') {
        return false;
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeDesc"></a>[module svgo.removeDesc](#apidoc.module.svgo.removeDesc)

#### <a name="apidoc.element.svgo.removeDesc.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeDesc.</span>fn (item, params)](#apidoc.element.svgo.removeDesc.fn)
- description and source-code
```javascript
fn = function (item, params) {

    return !item.isElem('desc') || !(params.removeAny || item.isEmpty() ||
            standardDescs.test(item.content[0].text));

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeDimensions"></a>[module svgo.removeDimensions](#apidoc.module.svgo.removeDimensions)

#### <a name="apidoc.element.svgo.removeDimensions.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeDimensions.</span>fn (item)](#apidoc.element.svgo.removeDimensions.fn)
- description and source-code
```javascript
fn = function (item) {

    if (
        item.isElem('svg') &&
        item.hasAttr('viewBox')
    ) {
        item.removeAttr('width');
        item.removeAttr('height');
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeDoctype"></a>[module svgo.removeDoctype](#apidoc.module.svgo.removeDoctype)

#### <a name="apidoc.element.svgo.removeDoctype.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeDoctype.</span>fn (item)](#apidoc.element.svgo.removeDoctype.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.doctype) {
        return false;
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeEditorsNSData"></a>[module svgo.removeEditorsNSData](#apidoc.module.svgo.removeEditorsNSData)

#### <a name="apidoc.element.svgo.removeEditorsNSData.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeEditorsNSData.</span>fn (item, params)](#apidoc.element.svgo.removeEditorsNSData.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (Array.isArray(params.additionalNamespaces)) {
        editorNamespaces = editorNamespaces.concat(params.additionalNamespaces);
    }

    if (item.elem) {

        if (item.isElem('svg')) {

            item.eachAttr(function(attr) {
                if (attr.prefix === 'xmlns' && editorNamespaces.indexOf(attr.value) > -1) {
                    prefixes.push(attr.local);

                    // <svg xmlns:sodipodi="">
                    item.removeAttr(attr.name);
                }
            });

        }

        // <* sodipodi:*="">
        item.eachAttr(function(attr) {
            if (prefixes.indexOf(attr.prefix) > -1) {
                item.removeAttr(attr.name);
            }
        });

        // <sodipodi:*>
        if (prefixes.indexOf(item.prefix) > -1) {
            return false;
        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeElementsByAttr"></a>[module svgo.removeElementsByAttr](#apidoc.module.svgo.removeElementsByAttr)

#### <a name="apidoc.element.svgo.removeElementsByAttr.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeElementsByAttr.</span>fn (item, params)](#apidoc.element.svgo.removeElementsByAttr.fn)
- description and source-code
```javascript
fn = function (item, params) {
    var elemId, elemClass;

    // wrap params in an array if not already
    ['id', 'class'].forEach(function(key) {
        if (!Array.isArray(params[key])) {
            params[key] = [ params[key] ];
        }
    });

    // abort if current item is no an element
    if (!item.isElem()) {
        return;
    }

    // remove element if it's 'id' matches configured 'id' params
    elemId = item.attr('id');
    if (elemId) {
        return params.id.indexOf(elemId.value) === -1;
    }

    // remove element if it's 'class' contains any of the configured 'class' params
    elemClass = item.attr('class');
    if (elemClass) {
        var hasClassRegex = new RegExp(params.class.join('|'));
        return !hasClassRegex.test(elemClass.value);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeEmptyAttrs"></a>[module svgo.removeEmptyAttrs](#apidoc.module.svgo.removeEmptyAttrs)

#### <a name="apidoc.element.svgo.removeEmptyAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeEmptyAttrs.</span>fn (item)](#apidoc.element.svgo.removeEmptyAttrs.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.elem) {

        item.eachAttr(function(attr) {
            if (attr.value === '') {
                item.removeAttr(attr.name);
            }
        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeEmptyContainers"></a>[module svgo.removeEmptyContainers](#apidoc.module.svgo.removeEmptyContainers)

#### <a name="apidoc.element.svgo.removeEmptyContainers.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeEmptyContainers.</span>fn (item)](#apidoc.element.svgo.removeEmptyContainers.fn)
- description and source-code
```javascript
fn = function (item) {

    return !(item.isElem(container) && !item.isElem('svg') && item.isEmpty() &&
        (!item.isElem('pattern') || !item.hasAttrLocal('href')));

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeEmptyText"></a>[module svgo.removeEmptyText](#apidoc.module.svgo.removeEmptyText)

#### <a name="apidoc.element.svgo.removeEmptyText.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeEmptyText.</span>fn (item, params)](#apidoc.element.svgo.removeEmptyText.fn)
- description and source-code
```javascript
fn = function (item, params) {

    // Remove empty text element
    if (
        params.text &&
        item.isElem('text') &&
        item.isEmpty()
    ) return false;

    // Remove empty tspan element
    if (
        params.tspan &&
        item.isElem('tspan') &&
        item.isEmpty()
    ) return false;

    // Remove tref with empty xlink:href attribute
    if (
        params.tref &&
        item.isElem('tref') &&
        !item.hasAttrLocal('href')
    ) return false;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeHiddenElems"></a>[module svgo.removeHiddenElems](#apidoc.module.svgo.removeHiddenElems)

#### <a name="apidoc.element.svgo.removeHiddenElems.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeHiddenElems.</span>fn (item, params)](#apidoc.element.svgo.removeHiddenElems.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.elem) {

        // display="none"
        //
        // http://www.w3.org/TR/SVG/painting.html#DisplayProperty
        // "A value of display: none indicates that the given element
        // and its children shall not be rendered directly"
        if (
            params.displayNone &&
            item.hasAttr('display', 'none')
        ) return false;

        // opacity="0"
        //
        // http://www.w3.org/TR/SVG/masking.html#ObjectAndGroupOpacityProperties
        if (
            params.opacity0 &&
            item.hasAttr('opacity', '0')
        ) return false;

        // Circles with zero radius
        //
        // http://www.w3.org/TR/SVG/shapes.html#CircleElementRAttribute
        // "A value of zero disables rendering of the element"
        //
        // <circle r="0">
        if (
            params.circleR0 &&
            item.isElem('circle') &&
            item.isEmpty() &&
            item.hasAttr('r', '0')
        ) return false;

        // Ellipse with zero x-axis radius
        //
        // http://www.w3.org/TR/SVG/shapes.html#EllipseElementRXAttribute
        // "A value of zero disables rendering of the element"
        //
        // <ellipse rx="0">
        if (
            params.ellipseRX0 &&
            item.isElem('ellipse') &&
            item.isEmpty() &&
            item.hasAttr('rx', '0')
        ) return false;

        // Ellipse with zero y-axis radius
        //
        // http://www.w3.org/TR/SVG/shapes.html#EllipseElementRYAttribute
        // "A value of zero disables rendering of the element"
        //
        // <ellipse ry="0">
        if (
            params.ellipseRY0 &&
            item.isElem('ellipse') &&
            item.isEmpty() &&
            item.hasAttr('ry', '0')
        ) return false;

        // Rectangle with zero width
        //
        // http://www.w3.org/TR/SVG/shapes.html#RectElementWidthAttribute
        // "A value of zero disables rendering of the element"
        //
        // <rect width="0">
        if (
            params.rectWidth0 &&
            item.isElem('rect') &&
            item.isEmpty() &&
            item.hasAttr('width', '0')
        ) return false;

        // Rectangle with zero height
        //
        // http://www.w3.org/TR/SVG/shapes.html#RectElementHeightAttribute
        // "A value of zero disables rendering of the element"
        //
        // <rect height="0">
        if (
            params.rectHeight0 &&
            params.rectWidth0 &&
            item.isElem('rect') &&
            item.isEmpty() &&
            item.hasAttr('height', '0')
        ) return false;

        // Pattern with zero width
        //
        // http://www.w3.org/TR/SVG/pservers.html#PatternElementWidthAttribute
        // "A value of zero disables rendering of the element (i.e., no paint is applied)"
        //
        // <pattern width="0">
        if (
            params.patternWidth0 &&
            item.isElem('pattern') &&
            item.hasAttr('width', '0')
        ) return false;

        // Pattern with zero height
        //
        // http://www.w3.org/TR/SVG/pservers.html#PatternElementHeightAttribute
        // "A value of zero disables rendering of the element (i.e., no paint is applied)"
        //
        // <pattern height="0">
        if (
            params.patternHeight0 &&
            item.isElem('pattern') &&
            item.hasAttr('height', '0')
        ) return false;

        // Image with zero width
        //
        // http://www.w3.org/TR/SVG/struct.html#ImageElementWidthAttribute
        // "A value of zero disables rendering of the element"
        //
        // <image width="0">
        if (
            params.imageWidth0 &&
            item.isElem('image') &&
            item.hasAttr('width', '0')
        ) return false;

        // Image with zero height
        //
        // http://www.w3.org/TR/SVG/struct.html#ImageElementHeightAttribute
        // "A value of zero disables rendering of the element"
        //
        // <image height="0">
        if ( ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeMetadata"></a>[module svgo.removeMetadata](#apidoc.module.svgo.removeMetadata)

#### <a name="apidoc.element.svgo.removeMetadata.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeMetadata.</span>fn (item)](#apidoc.element.svgo.removeMetadata.fn)
- description and source-code
```javascript
fn = function (item) {

    return !item.isElem('metadata');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeNonInheritableGroupAttrs"></a>[module svgo.removeNonInheritableGroupAttrs](#apidoc.module.svgo.removeNonInheritableGroupAttrs)

#### <a name="apidoc.element.svgo.removeNonInheritableGroupAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeNonInheritableGroupAttrs.</span>fn (item)](#apidoc.element.svgo.removeNonInheritableGroupAttrs.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.isElem('g')) {

        item.eachAttr(function(attr) {
            if (
                ~attrsGroups.presentation.indexOf(attr.name) &&
                ~attrsGroups.graphicalEvent.indexOf(attr.name) &&
                ~attrsGroups.core.indexOf(attr.name) &&
                ~attrsGroups.conditionalProcessing.indexOf(attr.name) &&
                !~excludedAttrs.indexOf(attr.name) &&
                !~inheritableAttrs.indexOf(attr.name)
            ) {
                item.removeAttr(attr.name);
            }
        });

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeRasterImages"></a>[module svgo.removeRasterImages](#apidoc.module.svgo.removeRasterImages)

#### <a name="apidoc.element.svgo.removeRasterImages.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeRasterImages.</span>fn (item)](#apidoc.element.svgo.removeRasterImages.fn)
- description and source-code
```javascript
fn = function (item) {

    if (
        item.isElem('image') &&
        item.hasAttrLocal('href', /(\.|image\/)(jpg|png|gif)/)
    ) {
        return false;
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeStyleElement"></a>[module svgo.removeStyleElement](#apidoc.module.svgo.removeStyleElement)

#### <a name="apidoc.element.svgo.removeStyleElement.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeStyleElement.</span>fn (item)](#apidoc.element.svgo.removeStyleElement.fn)
- description and source-code
```javascript
fn = function (item) {

    return !item.isElem('style');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeTitle"></a>[module svgo.removeTitle](#apidoc.module.svgo.removeTitle)

#### <a name="apidoc.element.svgo.removeTitle.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeTitle.</span>fn (item)](#apidoc.element.svgo.removeTitle.fn)
- description and source-code
```javascript
fn = function (item) {

    return !item.isElem('title');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeUnknownsAndDefaults"></a>[module svgo.removeUnknownsAndDefaults](#apidoc.module.svgo.removeUnknownsAndDefaults)

#### <a name="apidoc.element.svgo.removeUnknownsAndDefaults.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeUnknownsAndDefaults.</span>fn (item, params)](#apidoc.element.svgo.removeUnknownsAndDefaults.fn)
- description and source-code
```javascript
fn = function (item, params) {

    // elems w/o namespace prefix
    if (item.isElem() && !item.prefix) {

        var elem = item.elem;

        // remove unknown element's content
        if (
            params.unknownContent &&
            !item.isEmpty() &&
            elems[elem] && // make sure we know of this element before checking its children
            elem !== 'foreignObject' // Don't check foreignObject
        ) {
            item.content.forEach(function(content, i) {
                if (
                    content.isElem() &&
                    !content.prefix &&
                    (
                        (
                            elems[elem].content && // Do we have a record of its permitted content?
                            elems[elem].content.indexOf(content.elem) === -1
                        ) ||
                        (
                            !elems[elem].content && // we dont know about its permitted content
                            !elems[content.elem] // check that we know about the element at all
                        )
                    )
                ) {
                    item.content.splice(i, 1);
                }
            });
        }

        // remove element's unknown attrs and attrs with default values
        if (elems[elem] && elems[elem].attrs) {

            item.eachAttr(function(attr) {

                if (
                    attr.name !== 'xmlns' &&
                    (attr.prefix === 'xml' || !attr.prefix) &&
                    (!params.keepDataAttrs || attr.name.indexOf('data-') != 0)
                ) {
                    if (
                        // unknown attrs
                        (
                            params.unknownAttrs &&
                            elems[elem].attrs.indexOf(attr.name) === -1
                        ) ||
                        // attrs with default values
                        (
                            params.defaultAttrs &&
                            elems[elem].defaults &&
                            elems[elem].defaults[attr.name] === attr.value && (
                                attrsInheritable.indexOf(attr.name) < 0 ||
                                !item.parentNode.computedAttr(attr.name)
                            )
                        ) ||
                        // useless overrides
                        (
                            params.uselessOverrides &&
                            attr.name !== 'transform' &&
                            attrsInheritable.indexOf(attr.name) > -1 &&
                            item.parentNode.computedAttr(attr.name, attr.value)
                        )
                    ) {
                        item.removeAttr(attr.name);
                    }
                }

            });

        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeUnusedNS"></a>[module svgo.removeUnusedNS](#apidoc.module.svgo.removeUnusedNS)

#### <a name="apidoc.element.svgo.removeUnusedNS.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeUnusedNS.</span>fn (data)](#apidoc.element.svgo.removeUnusedNS.fn)
- description and source-code
```javascript
fn = function (data) {

    var svgElem,
        xmlnsCollection = [];

<span class="apidocCodeCommentSpan">    /**
     * Remove namespace from collection.
     *
     * @param {String} ns namescape name
     */
</span>    function removeNSfromCollection(ns) {

        var pos = xmlnsCollection.indexOf(ns);

        // if found - remove ns from the namespaces collection
        if (pos > -1) {
            xmlnsCollection.splice(pos, 1);
        }

    }

    /**
     * Bananas!
     *
     * @param {Array} items input items
     *
     * @return {Array} output items
     */
    function monkeys(items) {

        var i = 0,
            length = items.content.length;

        while(i < length) {

            var item = items.content[i];

            if (item.isElem('svg')) {

                item.eachAttr(function(attr) {
                    // collect namespaces
                    if (attr.prefix === 'xmlns' && attr.local) {
                        xmlnsCollection.push(attr.local);
                    }
                });

                // if svg element has ns-attr
                if (xmlnsCollection.length) {
                    // save svg element
                    svgElem = item;
                }

            } else if (xmlnsCollection.length) {

                // check item for the ns-attrs
                if (item.prefix) {
                    removeNSfromCollection(item.prefix);
                }

                // check each attr for the ns-attrs
                item.eachAttr(function(attr) {
                    removeNSfromCollection(attr.prefix);
                });

            }

            // if nothing is found - go deeper
            if (xmlnsCollection.length && item.content) {
                monkeys(item);
            }

            i++;

        }

        return items;

    }

    data = monkeys(data);

    // remove svg element ns-attributes if they are not used even once
    if (xmlnsCollection.length) {
        xmlnsCollection.forEach(function(name) {
            svgElem.removeAttr('xmlns:' + name);
        });
    }

    return data;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeUselessDefs"></a>[module svgo.removeUselessDefs](#apidoc.module.svgo.removeUselessDefs)

#### <a name="apidoc.element.svgo.removeUselessDefs.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeUselessDefs.</span>fn (item)](#apidoc.element.svgo.removeUselessDefs.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.isElem('defs')) {

        defs = item;
        item.content = (item.content || []).reduce(getUsefulItems, []);

        if (item.isEmpty()) return false;

    } else if (item.isElem(nonRendering) && !item.hasAttr('id')) {

        return false;

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeUselessStrokeAndFill"></a>[module svgo.removeUselessStrokeAndFill](#apidoc.module.svgo.removeUselessStrokeAndFill)

#### <a name="apidoc.element.svgo.removeUselessStrokeAndFill.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeUselessStrokeAndFill.</span>fn (item, params)](#apidoc.element.svgo.removeUselessStrokeAndFill.fn)
- description and source-code
```javascript
fn = function (item, params) {

    if (item.isElem(styleOrScript)) {
        hasStyleOrScript = true;
    }

    if (!hasStyleOrScript && item.isElem(shape) && !item.computedAttr('id')) {

        var stroke = params.stroke && item.computedAttr('stroke'),
            fill = params.fill && !item.computedAttr('fill', 'none');

        // remove stroke*
        if (
            params.stroke &&
            (!stroke ||
                stroke == 'none' ||
                item.computedAttr('stroke-opacity', '0') ||
                item.computedAttr('stroke-width', '0')
            )
        ) {
            var parentStroke = item.parentNode.computedAttr('stroke'),
                declineStroke = parentStroke && parentStroke != 'none';

            item.eachAttr(function(attr) {
                if (regStrokeProps.test(attr.name)) {
                    item.removeAttr(attr.name);
                }
            });

            if (declineStroke) item.addAttr({
                name: 'stroke',
                value: 'none',
                prefix: '',
                local: 'stroke'
            });
        }

        // remove fill*
        if (
            params.fill &&
            (!fill || item.computedAttr('fill-opacity', '0'))
        ) {
            item.eachAttr(function(attr) {
                if (regFillProps.test(attr.name)) {
                    item.removeAttr(attr.name);
                }
            });

            if (fill) {
                if (item.hasAttr('fill'))
                    item.attr('fill').value = 'none';
                else
                    item.addAttr({
                        name: 'fill',
                        value: 'none',
                        prefix: '',
                        local: 'fill'
                    });
            }
        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeViewBox"></a>[module svgo.removeViewBox](#apidoc.module.svgo.removeViewBox)

#### <a name="apidoc.element.svgo.removeViewBox.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeViewBox.</span>fn (item)](#apidoc.element.svgo.removeViewBox.fn)
- description and source-code
```javascript
fn = function (item) {

    if (
        item.isElem(viewBoxElems) &&
        item.hasAttr('viewBox') &&
        item.hasAttr('width') &&
        item.hasAttr('height')
    ) {

        var match = item.attr('viewBox').value.match(regViewBox);

        if (match) {
            if (
                item.attr('width').value === match[1] &&
                item.attr('height').value === match[3]
            ) {
                item.removeAttr('viewBox');
            }
        }

    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeXMLNS"></a>[module svgo.removeXMLNS](#apidoc.module.svgo.removeXMLNS)

#### <a name="apidoc.element.svgo.removeXMLNS.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeXMLNS.</span>fn (item)](#apidoc.element.svgo.removeXMLNS.fn)
- description and source-code
```javascript
fn = function (item) {

    if (item.isElem('svg') && item.hasAttr('xmlns')) {
        item.removeAttr('xmlns');
    }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.removeXMLProcInst"></a>[module svgo.removeXMLProcInst](#apidoc.module.svgo.removeXMLProcInst)

#### <a name="apidoc.element.svgo.removeXMLProcInst.fn"></a>[function <span class="apidocSignatureSpan">svgo.removeXMLProcInst.</span>fn (item)](#apidoc.element.svgo.removeXMLProcInst.fn)
- description and source-code
```javascript
fn = function (item) {

    return !(item.processinginstruction && item.processinginstruction.name === 'xml');

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.sortAttrs"></a>[module svgo.sortAttrs](#apidoc.module.svgo.sortAttrs)

#### <a name="apidoc.element.svgo.sortAttrs.fn"></a>[function <span class="apidocSignatureSpan">svgo.sortAttrs.</span>fn (item, params)](#apidoc.element.svgo.sortAttrs.fn)
- description and source-code
```javascript
fn = function (item, params) {

	var attrs = [],
		sorted = {},
		orderlen = params.order.length + 1;

	if (item.elem) {

		item.eachAttr(function(attr) {
			attrs.push(attr);
		});

		attrs.sort(function(a, b) {
			if (a.prefix != b.prefix) {
				// xmlns attributes implicitly have the prefix xmlns
				if (a.prefix == 'xmlns')
					return -1;
				if (b.prefix == 'xmlns')
					return 1;
				return a.prefix < b.prefix ? -1 : 1;
			}

			var aindex = orderlen;
			var bindex = orderlen;

			for (var i = 0; i < params.order.length; i++) {
				if (a.name == params.order[i]) {
					aindex = i;
				} else if (a.name.indexOf(params.order[i] + '-') === 0) {
					aindex = i + .5;
				}
				if (b.name == params.order[i]) {
					bindex = i;
				} else if (b.name.indexOf(params.order[i] + '-') === 0) {
					bindex = i + .5;
				}
			}

			if (aindex != bindex) {
				return aindex - bindex;
			}
			return a.name < b.name ? -1 : 1;
		});

		attrs.forEach(function (attr) {
			sorted[attr.name] = attr;
		});

		item.attrs = sorted;

	}

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.svgo.transformsWithOnePath"></a>[module svgo.transformsWithOnePath](#apidoc.module.svgo.transformsWithOnePath)

#### <a name="apidoc.element.svgo.transformsWithOnePath.fn"></a>[function <span class="apidocSignatureSpan">svgo.transformsWithOnePath.</span>fn (data, params)](#apidoc.element.svgo.transformsWithOnePath.fn)
- description and source-code
```javascript
fn = function (data, params) {

    data.content.forEach(function(item) {

        // only for SVG with one Path inside
        if (item.isElem('svg') &&
            item.content.length === 1 &&
            item.content[0].isElem('path')
        ) {

            var svgElem = item,
                pathElem = svgElem.content[0],
                // get absoluted Path data
                path = relative2absolute(EXTEND(true, [], path2js(pathElem))),
                xs = [],
                ys = [],
                cubicСontrolPoint = [0, 0],
                quadraticСontrolPoint = [0, 0],
                lastPoint = [0, 0],
                cubicBoundingBox,
                quadraticBoundingBox,
                i,
                segment;

            path.forEach(function(pathItem) {

                // ML
                if ('ML'.indexOf(pathItem.instruction) > -1) {

                    for (i = 0; i < pathItem.data.length; i++) {
                        if (i % 2 === 0) {
                            xs.push(pathItem.data[i]);
                        } else {
                            ys.push(pathItem.data[i]);
                        }
                    }

                    lastPoint = cubicСontrolPoint = quadraticСontrolPoint = pathItem.data.slice(-2);

                // H
                } else if (pathItem.instruction === 'H') {

                    pathItem.data.forEach(function(d) {
                        xs.push(d);
                    });

                    lastPoint[0] = cubicСontrolPoint[0] = quadraticСontrolPoint[0] = pathItem.data[pathItem.data.length - 2];

                // V
                } else if (pathItem.instruction === 'V') {

                    pathItem.data.forEach(function(d) {
                        ys.push(d);
                    });

                    lastPoint[1] = cubicСontrolPoint[1] = quadraticСontrolPoint[1] = pathItem.data[pathItem.data.length - 1];

                // C
                } else if (pathItem.instruction === 'C') {

                    for (i = 0; i < pathItem.data.length; i += 6) {

                        segment = pathItem.data.slice(i, i + 6);

                        cubicBoundingBox = computeCubicBoundingBox.apply(this, lastPoint.concat(segment));

                        xs.push(cubicBoundingBox.minx);
                        xs.push(cubicBoundingBox.maxx);

                        ys.push(cubicBoundingBox.miny);
                        ys.push(cubicBoundingBox.maxy);

                        // reflected control point for the next possible S
                        cubicСontrolPoint = [
                            2 * segment[4] - segment[2],
                            2 * segment[5] - segment[3]
                        ];

                        lastPoint = segment.slice(-2);

                    }

                // S
                } else if (pathItem.instruction === 'S') {

                    for (i = 0; i < pathItem.data.length; i += 4) {

                        segment = pathItem.data.slice(i, i + 4);

                        cubicBoundingBox = computeCubicBoundingBox.apply(this, lastPoint.concat(cubicСontrolPoint).concat(segment
));

                        xs.push(cubicBoundingBox.minx);
                        xs.push(cubicBoundingBox.maxx);

                        ys.push(cubicBoundingBox.miny);
                        ys.push(cubicBoundingBox.maxy);

                        // reflected control point for the next possible S
                        cubicСontrolPoint = [
                            2 * segment[2] - cubicСontrolPoint[0],
                            2 * segment[3] - cubicСontrolPoint[1],
                        ];

                        lastPoint = segment.slice(-2);

                    }

                // Q
                } else if (pathItem.instruction === 'Q') {

                    for (i = 0; i < pathItem.data.length; i += 4) {

                        segment = pathItem.data.slice(i, i + 4);

                        quadraticBoundingBox = computeQuadraticBoundingBox.apply(this, lastPoint.concat(segment)); ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
