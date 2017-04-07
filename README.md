# api documentation for  [replacestream (v4.0.2)](https://github.com/eugeneware/replacestream#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-replacestream.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-replacestream) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-replacestream.svg)](https://travis-ci.org/npmdoc/node-npmdoc-replacestream)
#### A node.js through stream that does basic streaming text search and replace and is chunk boundary friendly

[![NPM](https://nodei.co/npm/replacestream.png?downloads=true)](https://www.npmjs.com/package/replacestream)

[![apidoc](https://npmdoc.github.io/node-npmdoc-replacestream/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-replacestream_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-replacestream/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-replacestream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-replacestream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eugene Ware",
        "email": "eugene@noblesamurai.com"
    },
    "bugs": {
        "url": "https://github.com/eugeneware/replacestream/issues"
    },
    "dependencies": {
        "escape-string-regexp": "^1.0.3",
        "object-assign": "^4.0.1",
        "readable-stream": "^2.0.2"
    },
    "description": "A node.js through stream that does basic streaming text search and replace and is chunk boundary friendly",
    "devDependencies": {
        "chai": "^3.2.0",
        "concat-stream": "^1.5.0",
        "istanbul": "^0.3.18",
        "istanbul-coveralls": "^1.0.3",
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "0c4140707e4f0323f50de044851708cf58bc37bd",
        "tarball": "https://registry.npmjs.org/replacestream/-/replacestream-4.0.2.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "807e7e0e7e409cd0b58780394d9946bcefed943c",
    "homepage": "https://github.com/eugeneware/replacestream#readme",
    "keywords": [
        "replace",
        "text",
        "regex",
        "stream",
        "streams",
        "streaming",
        "search"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "eugeneware",
            "email": "eugene@noblesamurai.com"
        },
        {
            "name": "mehtaphysical",
            "email": "me@ryanmehta.me"
        },
        {
            "name": "shinnn",
            "email": "snnskwtnb@gmail.com"
        }
    ],
    "name": "replacestream",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eugeneware/replacestream.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "coveralls": "${npm_package_scripts_coverage} && istanbul-coveralls",
        "test": "mocha --growl --full-trace"
    },
    "version": "4.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module replacestream](#apidoc.module.replacestream)



# <a name="apidoc.module.replacestream"></a>[module replacestream](#apidoc.module.replacestream)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
