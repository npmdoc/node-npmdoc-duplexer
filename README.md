# api documentation for  [duplexer (v0.1.1)](https://github.com/Raynos/duplexer)  [![npm package](https://img.shields.io/npm/v/npmdoc-duplexer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-duplexer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-duplexer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-duplexer)
#### Creates a duplex stream

[![NPM](https://nodei.co/npm/duplexer.png?downloads=true)](https://www.npmjs.com/package/duplexer)

[![apidoc](https://npmdoc.github.io/node-npmdoc-duplexer/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-duplexer_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-duplexer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-duplexer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-duplexer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos",
        "email": "raynos2@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/Raynos/duplexer/issues",
        "email": "raynos2@gmail.com"
    },
    "contributors": [
        {
            "name": "Jake Verbaten"
        }
    ],
    "dependencies": {},
    "description": "Creates a duplex stream",
    "devDependencies": {
        "tape": "0.3.3",
        "through": "~0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "ace6ff808c1ce66b57d1ebf97977acb02334cfc1",
        "tarball": "https://registry.npmjs.org/duplexer/-/duplexer-0.1.1.tgz"
    },
    "homepage": "https://github.com/Raynos/duplexer",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/duplexer/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos",
            "email": "raynos2@gmail.com"
        },
        {
            "name": "dominictarr",
            "email": "dominic.tarr@gmail.com"
        }
    ],
    "name": "duplexer",
    "optionalDependencies": {},
    "readme": "# duplexer\n\n[![build status][1]][2] [![dependency status][3]][4]\n\n[![browser support][5]][6]\n\nCreates a duplex stream\n\nTaken from [event-stream][7]\n\n## duplex (writeStream, readStream)\n\nTakes a writable stream and a readable stream and makes them appear as a readable writable stream.\n\nIt is assumed that the two streams are connected to each other in some way.\n\n## Example\n\n'''js\nvar grep = cp.exec('grep Stream')\n\nduplex(grep.stdin, grep.stdout)\n'''\n\n## Installation\n\n'npm install duplexer'\n\n## Tests\n\n'npm test'\n\n## Contributors\n\n - Dominictarr\n - Raynos\n - samccone\n\n## MIT Licenced\n\n  [1]: https://secure.travis-ci.org/Raynos/duplexer.png\n  [2]: https://travis-ci.org/Raynos/duplexer\n  [3]: https://david-dm.org/Raynos/duplexer.png\n  [4]: https://david-dm.org/Raynos/duplexer\n  [5]: https://ci.testling.com/Raynos/duplexer.png\n  [6]: https://ci.testling.com/Raynos/duplexer\n  [7]: https://github.com/dominictarr/event-stream#duplex-writestream-readstream\n",
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/duplexer.git"
    },
    "scripts": {
        "test": "node test"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest"
        ]
    },
    "version": "0.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module duplexer](#apidoc.module.duplexer)



# <a name="apidoc.module.duplexer"></a>[module duplexer](#apidoc.module.duplexer)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
