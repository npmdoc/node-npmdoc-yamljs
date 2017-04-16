# api documentation for  [yamljs (v0.2.9)](https://github.com/jeremyfa/yaml.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yamljs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yamljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yamljs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yamljs)
#### Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.

[![NPM](https://nodei.co/npm/yamljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yamljs)

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
        "shasum": "bd3bdaa62ac09deb2a2e1ce803eeb4217b52a82f",
        "tarball": "https://registry.npmjs.org/yamljs/-/yamljs-0.2.9.tgz"
    },
    "gitHead": "e1796d46972b4784973d7593802975af0d138547",
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
    "version": "0.2.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module yamljs](#apidoc.module.yamljs)
1.  [function <span class="apidocSignatureSpan"></span>yamljs ()](#apidoc.element.yamljs.yamljs)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>dump (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.dump)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>load (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.load)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>parse (input, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parse)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>parseFile (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parseFile)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>register ()](#apidoc.element.yamljs.register)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>stringify (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.stringify)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>toString ()](#apidoc.element.yamljs.toString)



# <a name="apidoc.module.yamljs"></a>[module yamljs](#apidoc.module.yamljs)

#### <a name="apidoc.element.yamljs.yamljs"></a>[function <span class="apidocSignatureSpan"></span>yamljs ()](#apidoc.element.yamljs.yamljs)
- description and source-code
```javascript
function Yaml() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.dump"></a>[function <span class="apidocSignatureSpan">yamljs.</span>dump (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.dump)
- description and source-code
```javascript
dump = function (input, inline, indent, exceptionOnInvalidType, objectEncoder) {
  var yaml;
  if (inline == null) {
    inline = 2;
  }
  if (indent == null) {
    indent = 4;
  }
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectEncoder == null) {
    objectEncoder = null;
  }
  yaml = new Dumper();
  yaml.indentation = indent;
  return yaml.dump(input, inline, 0, exceptionOnInvalidType, objectEncoder);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.load"></a>[function <span class="apidocSignatureSpan">yamljs.</span>load (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.load)
- description and source-code
```javascript
load = function (path, callback, exceptionOnInvalidType, objectDecoder) {
  return this.parseFile(path, callback, exceptionOnInvalidType, objectDecoder);
}
```
- example usage
```shell
...
''' js
yamlString = YAML.stringify(nativeObject[, inline /* @integer depth to start using inline notation at */[, spaces /* @integer number
 of spaces to use for indentation */] ]);
'''

Load yaml file:

''' js
nativeObject = YAML.load('file.yml');
'''

Load yaml file:

''' js
YAML.load('file.yml', function(result)
{
...
```

#### <a name="apidoc.element.yamljs.parse"></a>[function <span class="apidocSignatureSpan">yamljs.</span>parse (input, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parse)
- description and source-code
```javascript
parse = function (input, exceptionOnInvalidType, objectDecoder) {
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectDecoder == null) {
    objectDecoder = null;
  }
  return new Parser().parse(input, exceptionOnInvalidType, objectDecoder);
}
```
- example usage
```shell
...
''' html
<script type="text/javascript" src="yaml.js"></script>
'''

Parse yaml string:

''' js
nativeObject = YAML.parse(yamlString);
'''

Dump native object into yaml string:

''' js
yamlString = YAML.stringify(nativeObject[, inline /* @integer depth to start using inline notation at */[, spaces /* @integer number
 of spaces to use for indentation */] ]);
'''
...
```

#### <a name="apidoc.element.yamljs.parseFile"></a>[function <span class="apidocSignatureSpan">yamljs.</span>parseFile (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parseFile)
- description and source-code
```javascript
parseFile = function (path, callback, exceptionOnInvalidType, objectDecoder) {
  var input;
  if (callback == null) {
    callback = null;
  }
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectDecoder == null) {
    objectDecoder = null;
  }
  if (callback != null) {
    return Utils.getStringFromFile(path, (function(_this) {
      return function(input) {
        var result;
        result = null;
        if (input != null) {
          result = _this.parse(input, exceptionOnInvalidType, objectDecoder);
        }
        callback(result);
      };
    })(this));
  } else {
    input = Utils.getStringFromFile(path);
    if (input != null) {
      return this.parse(input, exceptionOnInvalidType, objectDecoder);
    }
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.register"></a>[function <span class="apidocSignatureSpan">yamljs.</span>register ()](#apidoc.element.yamljs.register)
- description and source-code
```javascript
register = function () {
  var require_handler;
  require_handler = function(module, filename) {
    return module.exports = YAML.parseFile(filename);
  };
  if ((typeof require !== "undefined" && require !== null ? require.extensions : void 0) != null) {
    require.extensions['.yml'] = require_handler;
    return require.extensions['.yaml'] = require_handler;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.stringify"></a>[function <span class="apidocSignatureSpan">yamljs.</span>stringify (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.stringify)
- description and source-code
```javascript
stringify = function (input, inline, indent, exceptionOnInvalidType, objectEncoder) {
  return this.dump(input, inline, indent, exceptionOnInvalidType, objectEncoder);
}
```
- example usage
```shell
...
''' js
nativeObject = YAML.parse(yamlString);
'''

Dump native object into yaml string:

''' js
yamlString = YAML.stringify(nativeObject[, inline /* @integer depth to start using inline notation at */[, spaces /* @integer number
 of spaces to use for indentation */] ]);
'''

Load yaml file:

''' js
nativeObject = YAML.load('file.yml');
'''
...
```

#### <a name="apidoc.element.yamljs.toString"></a>[function <span class="apidocSignatureSpan">yamljs.</span>toString ()](#apidoc.element.yamljs.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
