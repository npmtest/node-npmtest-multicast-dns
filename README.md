# npmtest-multicast-dns

#### basic test coverage for  [multicast-dns (v6.1.1)](https://github.com/mafintosh/multicast-dns)  [![npm package](https://img.shields.io/npm/v/npmtest-multicast-dns.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-multicast-dns) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-multicast-dns.svg)](https://travis-ci.org/npmtest/node-npmtest-multicast-dns)

#### Low level multicast-dns implementation in pure javascript

[![NPM](https://nodei.co/npm/multicast-dns.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/multicast-dns)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-multicast-dns/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-multicast-dns/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-multicast-dns/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-multicast-dns/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-multicast-dns/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-multicast-dns/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-multicast-dns/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-multicast-dns/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-multicast-dns/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-multicast-dns/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-multicast-dns/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-multicast-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-multicast-dns/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-multicast-dns/build/test-report.html](https://npmtest.github.io/node-npmtest-multicast-dns/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-multicast-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-multicast-dns/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-multicast-dns/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-multicast-dns/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-multicast-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-multicast-dns/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-multicast-dns/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-multicast-dns/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus",
        "url": "@mafintosh"
    },
    "bin": {
        "multicast-dns": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/multicast-dns/issues"
    },
    "coordinates": [
        55.6465878,
        12.5492251
    ],
    "dependencies": {
        "dns-packet": "^1.0.1",
        "thunky": "^0.1.0"
    },
    "description": "Low level multicast-dns implementation in pure javascript",
    "devDependencies": {
        "standard": "^5.4.1",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6e7de86a570872ab17058adea7160bbeca814dde",
        "tarball": "https://registry.npmjs.org/multicast-dns/-/multicast-dns-6.1.1.tgz"
    },
    "gitHead": "6b3e4ec0c281e51a87a67a005028a7b12e0c60ff",
    "homepage": "https://github.com/mafintosh/multicast-dns",
    "keywords": [
        "multicast",
        "dns",
        "mdns",
        "multicastdns",
        "dns-sd",
        "service",
        "discovery",
        "bonjour",
        "avahi"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "watson"
        }
    ],
    "name": "multicast-dns",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/multicast-dns.git"
    },
    "scripts": {
        "test": "standard && tape test.js"
    },
    "version": "6.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
