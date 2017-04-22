# npmdoc-yamljs

#### api documentation for  [yamljs (v0.2.10)](https://github.com/jeremyfa/yaml.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yamljs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yamljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yamljs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yamljs)

#### Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.

[![NPM](https://nodei.co/npm/yamljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yamljs)

- [https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yamljs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Faivre"
    },
    "bin": {
        "yaml2json": "./bin/yaml2json",
        "json2yaml": "./bin/json2yaml"
    },
    "bugs": {
        "url": "https://github.com/jeremyfa/yaml.js/issues"
    },
    "dependencies": {
        "argparse": "^1.0.7",
        "glob": "^7.0.5"
    },
    "description": "Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "coffeeify": "^2.0.1",
        "jasmine-node": "^1.14.5"
    },
    "directories": {},
    "dist": {
        "shasum": "481cc7c25ca73af59f591f0c96e3ce56c757a40f",
        "tarball": "https://registry.npmjs.org/yamljs/-/yamljs-0.2.10.tgz"
    },
    "gitHead": "305f32d3bd051b7f9506b47b666aab17415474d4",
    "homepage": "https://github.com/jeremyfa/yaml.js#readme",
    "keywords": [
        "yaml",
        "json",
        "yaml2json",
        "json2yaml"
    ],
    "license": "MIT",
    "main": "./lib/Yaml.js",
    "maintainers": [
        {
            "name": "jeremyfa"
        }
    ],
    "name": "yamljs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jeremyfa/yaml.js.git"
    },
    "scripts": {
        "test": "cake build; cake test"
    },
    "version": "0.2.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
