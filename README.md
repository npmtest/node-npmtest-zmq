# npmtest-zmq

#### basic test coverage for  zmq (v2.15.3)  [![npm package](https://img.shields.io/npm/v/npmtest-zmq.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zmq) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zmq.svg)](https://travis-ci.org/npmtest/node-npmtest-zmq)

#### Bindings for node.js and io.js to ZeroMQ

[![NPM](https://nodei.co/npm/zmq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zmq)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zmq/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zmq/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zmq/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zmq/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zmq/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zmq/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zmq/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zmq/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zmq/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zmq/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zmq/build/test-report.html](https://npmtest.github.io/node-npmtest-zmq/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zmq/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zmq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zmq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zmq/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zmq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zmq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "zmq",
    "version": "2.15.3",
    "description": "Bindings for node.js and io.js to ZeroMQ",
    "main": "index",
    "repository": {
        "type": "git",
        "url": "http://github.com/JustinTulloss/zeromq.node.git"
    },
    "dependencies": {
        "nan": "~2.3.0",
        "bindings": "~1.2.1"
    },
    "devDependencies": {
        "should": "2.1.x",
        "semver": "~4.1.1",
        "mocha": "~1.13.0"
    },
    "engines": {
        "node": ">=0.8"
    },
    "scripts": {
        "test": "mocha --expose-gc --slow 2000 --timeout 600000"
    },
    "keywords": [
        "zeromq",
        "zmq",
        "0mq",
        "ømq",
        "libzmq",
        "native",
        "binding",
        "addon"
    ],
    "license": "MIT",
    "author": "Justin Tulloss <justin.tulloss@gmail.com> (http://justin.harmonize.fm)",
    "contributors": [
        "Justin Tulloss <justin.tulloss@gmail.com> (http://justin.harmonize.fm)",
        "Stéphan Kochen <stephan@kochen.nl> (http://stephan.kochen.nl/)",
        "Mike Castleman <m@mlcastle.net> (http://mlcastle.net/)",
        "Matt Crocker",
        "Jeremy Barnes <jeremy@barneso.com> (http://www.barneso.com/)",
        "Rick <technoweenie@gmail.com> (http://techno-weenie.net/)",
        "Corey Jewett (http://syntheticplayground.com/)",
        "Micheil Smith <micheil@brandedcode.com> (http://brandedcode.com/)",
        "TJ Holowaychuk <tj@vision-media.ca> (http://tjholowaychuk.com/)",
        "Ron Korving (https://github.com/ronkorving)",
        "Mark Everitt (http://qubyte.dyndns.org/)",
        "Aldis Andrejevs (https://github.com/aaudis)",
        "Iskren Ivov Chernev <iskren.chernev@gmail.com>",
        "Seth Fitzsimmons",
        "Patrick Lucas",
        "Alexander Simmerl (https://github.com/xla)",
        "Ian Babrou",
        "Niall O'Higgins",
        "Brian White (https://github.com/mscdex)",
        "Mathieu D'Amours (https://github.com/matehat)",
        "Joshua Gourneau",
        "Yaroslav Shirokov",
        "Marc Harter (https://github.com/wavded)",
        "John Sun (https://github.com/freehaha)",
        "Alexey Kupershtokh <alexey.kupershtokh@gmail.com>",
        "Jon Gretar Borgthorsson (https://github.com/JonGretar)",
        "Brian Lalor (https://github.com/blalor)",
        "Benjamin Byholm (https://github.com/kkoopa)",
        "Alejandro (https://github.com/Minjung)",
        "Eli Skeggs <skeggse@gmail.com> (https://github.com/skeggse)",
        "Bent Cardan <bent@nothingsatisfies.com> (https://github.com/reqshark)"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
