# api documentation for  [yamljs (v0.2.9)](https://github.com/jeremyfa/yaml.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yamljs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yamljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yamljs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yamljs)
#### Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.

[![NPM](https://nodei.co/npm/yamljs.png?downloads=true)](https://www.npmjs.com/package/yamljs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-yamljs_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yamljs/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yamljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Faivre",
        "email": "contact@jeremyfa.com"
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
            "name": "jeremyfa",
            "email": "contact@jeremyfa.com"
        }
    ],
    "name": "yamljs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Dumper ()](#apidoc.element.yamljs.Dumper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Escaper ()](#apidoc.element.yamljs.Escaper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Inline ()](#apidoc.element.yamljs.Inline)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Parser (offset)](#apidoc.element.yamljs.Parser)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Pattern (rawRegex, modifiers)](#apidoc.element.yamljs.Pattern)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Unescaper ()](#apidoc.element.yamljs.Unescaper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Utils ()](#apidoc.element.yamljs.Utils)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>dump (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.dump)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>load (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.load)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>parse (input, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parse)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>parseFile (path, callback, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.parseFile)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>register ()](#apidoc.element.yamljs.register)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>stringify (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.stringify)
1.  object <span class="apidocSignatureSpan">yamljs.</span>Dumper.prototype
1.  object <span class="apidocSignatureSpan">yamljs.</span>Parser.prototype
1.  object <span class="apidocSignatureSpan">yamljs.</span>Pattern.prototype

#### [module yamljs.Dumper](#apidoc.module.yamljs.Dumper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Dumper ()](#apidoc.element.yamljs.Dumper.Dumper)
1.  number <span class="apidocSignatureSpan">yamljs.Dumper.</span>indentation

#### [module yamljs.Dumper.prototype](#apidoc.module.yamljs.Dumper.prototype)
1.  [function <span class="apidocSignatureSpan">yamljs.Dumper.prototype.</span>dump (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.Dumper.prototype.dump)

#### [module yamljs.Escaper](#apidoc.module.yamljs.Escaper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Escaper ()](#apidoc.element.yamljs.Escaper.Escaper)
1.  [function <span class="apidocSignatureSpan">yamljs.Escaper.</span>escapeWithDoubleQuotes (value)](#apidoc.element.yamljs.Escaper.escapeWithDoubleQuotes)
1.  [function <span class="apidocSignatureSpan">yamljs.Escaper.</span>escapeWithSingleQuotes (value)](#apidoc.element.yamljs.Escaper.escapeWithSingleQuotes)
1.  [function <span class="apidocSignatureSpan">yamljs.Escaper.</span>requiresDoubleQuoting (value)](#apidoc.element.yamljs.Escaper.requiresDoubleQuoting)
1.  [function <span class="apidocSignatureSpan">yamljs.Escaper.</span>requiresSingleQuoting (value)](#apidoc.element.yamljs.Escaper.requiresSingleQuoting)
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>LIST_ESCAPED
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>LIST_ESCAPEES
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>MAPPING_ESCAPEES_TO_ESCAPED
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>PATTERN_CHARACTERS_TO_ESCAPE
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>PATTERN_MAPPING_ESCAPEES
1.  object <span class="apidocSignatureSpan">yamljs.Escaper.</span>PATTERN_SINGLE_QUOTING

#### [module yamljs.Inline](#apidoc.module.yamljs.Inline)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Inline ()](#apidoc.element.yamljs.Inline.Inline)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>configure (exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Inline.configure)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>dump (value, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.Inline.dump)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>dumpObject (value, exceptionOnInvalidType, objectSupport)](#apidoc.element.yamljs.Inline.dumpObject)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>evaluateScalar (scalar, context)](#apidoc.element.yamljs.Inline.evaluateScalar)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>parse (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Inline.parse)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseMapping (mapping, context)](#apidoc.element.yamljs.Inline.parseMapping)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseQuotedScalar (scalar, context)](#apidoc.element.yamljs.Inline.parseQuotedScalar)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseScalar (scalar, delimiters, stringDelimiters, context, evaluate)](#apidoc.element.yamljs.Inline.parseScalar)
1.  [function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseSequence (sequence, context)](#apidoc.element.yamljs.Inline.parseSequence)
1.  object <span class="apidocSignatureSpan">yamljs.Inline.</span>PATTERN_QUOTED_SCALAR
1.  object <span class="apidocSignatureSpan">yamljs.Inline.</span>PATTERN_SCALAR_BY_DELIMITERS
1.  object <span class="apidocSignatureSpan">yamljs.Inline.</span>PATTERN_THOUSAND_NUMERIC_SCALAR
1.  object <span class="apidocSignatureSpan">yamljs.Inline.</span>PATTERN_TRAILING_COMMENTS
1.  object <span class="apidocSignatureSpan">yamljs.Inline.</span>settings
1.  string <span class="apidocSignatureSpan">yamljs.Inline.</span>REGEX_QUOTED_STRING

#### [module yamljs.Parser](#apidoc.module.yamljs.Parser)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Parser (offset)](#apidoc.element.yamljs.Parser.Parser)

#### [module yamljs.Parser.prototype](#apidoc.module.yamljs.Parser.prototype)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>cleanup (value)](#apidoc.element.yamljs.Parser.prototype.cleanup)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getCurrentLineIndentation ()](#apidoc.element.yamljs.Parser.prototype.getCurrentLineIndentation)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getNextEmbedBlock (indentation, includeUnindentedCollection)](#apidoc.element.yamljs.Parser.prototype.getNextEmbedBlock)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getRealCurrentLineNb ()](#apidoc.element.yamljs.Parser.prototype.getRealCurrentLineNb)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineBlank ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineBlank)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineComment ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineComment)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineEmpty ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineEmpty)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isNextLineIndented (ignoreComments)](#apidoc.element.yamljs.Parser.prototype.isNextLineIndented)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isNextLineUnIndentedCollection (currentIndentation)](#apidoc.element.yamljs.Parser.prototype.isNextLineUnIndentedCollection)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isStringUnIndentedCollectionItem ()](#apidoc.element.yamljs.Parser.prototype.isStringUnIndentedCollectionItem)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>moveToNextLine ()](#apidoc.element.yamljs.Parser.prototype.moveToNextLine)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>moveToPreviousLine ()](#apidoc.element.yamljs.Parser.prototype.moveToPreviousLine)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parse (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Parser.prototype.parse)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parseFoldedScalar (separator, indicator, indentation)](#apidoc.element.yamljs.Parser.prototype.parseFoldedScalar)
1.  [function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parseValue (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Parser.prototype.parseValue)
1.  number <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>CONTEXT_MAPPING
1.  number <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>CONTEXT_NONE
1.  number <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>CONTEXT_SEQUENCE
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_ANCHOR_VALUE
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_COMPACT_NOTATION
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_DECIMAL
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_DOCUMENT_MARKER_END
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_DOCUMENT_MARKER_START
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_FOLDED_SCALAR_ALL
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_FOLDED_SCALAR_BY_INDENTATION
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_FOLDED_SCALAR_END
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_INDENT_SPACES
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_LEADING_COMMENTS
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_MAPPING_ITEM
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_SEQUENCE_ITEM
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_TRAILING_LINES
1.  object <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>PATTERN_YAML_HEADER

#### [module yamljs.Pattern](#apidoc.module.yamljs.Pattern)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Pattern (rawRegex, modifiers)](#apidoc.element.yamljs.Pattern.Pattern)

#### [module yamljs.Pattern.prototype](#apidoc.module.yamljs.Pattern.prototype)
1.  [function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>exec (str)](#apidoc.element.yamljs.Pattern.prototype.exec)
1.  [function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>replace (str, replacement)](#apidoc.element.yamljs.Pattern.prototype.replace)
1.  [function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>replaceAll (str, replacement, limit)](#apidoc.element.yamljs.Pattern.prototype.replaceAll)
1.  [function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>test (str)](#apidoc.element.yamljs.Pattern.prototype.test)
1.  object <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>cleanedRegex
1.  object <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>mapping
1.  object <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>rawRegex
1.  object <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>regex

#### [module yamljs.Unescaper](#apidoc.module.yamljs.Unescaper)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Unescaper ()](#apidoc.element.yamljs.Unescaper.Unescaper)
1.  [function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeCharacter (value)](#apidoc.element.yamljs.Unescaper.unescapeCharacter)
1.  [function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeDoubleQuotedString (value)](#apidoc.element.yamljs.Unescaper.unescapeDoubleQuotedString)
1.  [function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeSingleQuotedString (value)](#apidoc.element.yamljs.Unescaper.unescapeSingleQuotedString)
1.  object <span class="apidocSignatureSpan">yamljs.Unescaper.</span>PATTERN_ESCAPED_CHARACTER

#### [module yamljs.Utils](#apidoc.module.yamljs.Utils)
1.  [function <span class="apidocSignatureSpan">yamljs.</span>Utils ()](#apidoc.element.yamljs.Utils.Utils)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>getStringFromFile (path, callback)](#apidoc.element.yamljs.Utils.getStringFromFile)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>hexDec (input)](#apidoc.element.yamljs.Utils.hexDec)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>isDigits (input)](#apidoc.element.yamljs.Utils.isDigits)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>isEmpty (value)](#apidoc.element.yamljs.Utils.isEmpty)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>isEmptyObject (value)](#apidoc.element.yamljs.Utils.isEmptyObject)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>isNumeric (input)](#apidoc.element.yamljs.Utils.isNumeric)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>ltrim (str, _char)](#apidoc.element.yamljs.Utils.ltrim)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>octDec (input)](#apidoc.element.yamljs.Utils.octDec)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>parseBoolean (input, strict)](#apidoc.element.yamljs.Utils.parseBoolean)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>rtrim (str, _char)](#apidoc.element.yamljs.Utils.rtrim)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>strRepeat (str, number)](#apidoc.element.yamljs.Utils.strRepeat)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>stringToDate (str)](#apidoc.element.yamljs.Utils.stringToDate)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>subStrCount (string, subString, start, length)](#apidoc.element.yamljs.Utils.subStrCount)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>trim (str, _char)](#apidoc.element.yamljs.Utils.trim)
1.  [function <span class="apidocSignatureSpan">yamljs.Utils.</span>utf8chr (c)](#apidoc.element.yamljs.Utils.utf8chr)
1.  number <span class="apidocSignatureSpan">yamljs.Utils.</span>LOCAL_TIMEZONE_OFFSET
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>PATTERN_DATE
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_DIGITS
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_HEXADECIMAL
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_LEFT_TRIM_BY_CHAR
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_OCTAL
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_RIGHT_TRIM_BY_CHAR
1.  object <span class="apidocSignatureSpan">yamljs.Utils.</span>REGEX_SPACES



# <a name="apidoc.module.yamljs"></a>[module yamljs](#apidoc.module.yamljs)

#### <a name="apidoc.element.yamljs.Dumper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Dumper ()](#apidoc.element.yamljs.Dumper)
- description and source-code
```javascript
function Dumper() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Escaper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Escaper ()](#apidoc.element.yamljs.Escaper)
- description and source-code
```javascript
function Escaper() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Inline"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Inline ()](#apidoc.element.yamljs.Inline)
- description and source-code
```javascript
function Inline() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Parser"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Parser (offset)](#apidoc.element.yamljs.Parser)
- description and source-code
```javascript
function Parser(offset) {
  this.offset = offset != null ? offset : 0;
  this.lines = [];
  this.currentLineNb = -1;
  this.currentLine = '';
  this.refs = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Pattern"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Pattern (rawRegex, modifiers)](#apidoc.element.yamljs.Pattern)
- description and source-code
```javascript
function Pattern(rawRegex, modifiers) {
  var _char, capturingBracketNumber, cleanedRegex, i, len, mapping, name, part, subChar;
  if (modifiers == null) {
    modifiers = '';
  }
  cleanedRegex = '';
  len = rawRegex.length;
  mapping = null;
  capturingBracketNumber = 0;
  i = 0;
  while (i < len) {
    _char = rawRegex.charAt(i);
    if (_char === '\\') {
      cleanedRegex += rawRegex.slice(i, +(i + 1) + 1 || 9e9);
      i++;
    } else if (_char === '(') {
      if (i < len - 2) {
        part = rawRegex.slice(i, +(i + 2) + 1 || 9e9);
        if (part === '(?:') {
          i += 2;
          cleanedRegex += part;
        } else if (part === '(?<') {
          capturingBracketNumber++;
          i += 2;
          name = '';
          while (i + 1 < len) {
            subChar = rawRegex.charAt(i + 1);
            if (subChar === '>') {
              cleanedRegex += '(';
              i++;
              if (name.length > 0) {
                if (mapping == null) {
                  mapping = {};
                }
                mapping[name] = capturingBracketNumber;
              }
              break;
            } else {
              name += subChar;
            }
            i++;
          }
        } else {
          cleanedRegex += _char;
          capturingBracketNumber++;
        }
      } else {
        cleanedRegex += _char;
      }
    } else {
      cleanedRegex += _char;
    }
    i++;
  }
  this.rawRegex = rawRegex;
  this.cleanedRegex = cleanedRegex;
  this.regex = new RegExp(this.cleanedRegex, 'g' + modifiers.replace('g', ''));
  this.mapping = mapping;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Unescaper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Unescaper ()](#apidoc.element.yamljs.Unescaper)
- description and source-code
```javascript
function Unescaper() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Utils"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Utils ()](#apidoc.element.yamljs.Utils)
- description and source-code
```javascript
function Utils() {}
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
...
}
if (objectEncoder == null) {
  objectEncoder = null;
}
output = '';
prefix = (indent ? Utils.strRepeat(' ', indent) : '');
if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
  output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
} else {
  if (input instanceof Array) {
    for (i = 0, len = input.length; i < len; i++) {
      value = input[i];
      willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
      output += prefix + '-' + (willBeInlined ? ' ' : "\n") + this.dump(value, inline - 1, (willBeInlined ? 0 : indent + this.indentation
), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
    }
...
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



# <a name="apidoc.module.yamljs.Dumper"></a>[module yamljs.Dumper](#apidoc.module.yamljs.Dumper)

#### <a name="apidoc.element.yamljs.Dumper.Dumper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Dumper ()](#apidoc.element.yamljs.Dumper.Dumper)
- description and source-code
```javascript
function Dumper() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.yamljs.Dumper.prototype"></a>[module yamljs.Dumper.prototype](#apidoc.module.yamljs.Dumper.prototype)

#### <a name="apidoc.element.yamljs.Dumper.prototype.dump"></a>[function <span class="apidocSignatureSpan">yamljs.Dumper.prototype.</span>dump (input, inline, indent, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.Dumper.prototype.dump)
- description and source-code
```javascript
dump = function (input, inline, indent, exceptionOnInvalidType, objectEncoder) {
  var i, key, len, output, prefix, value, willBeInlined;
  if (inline == null) {
    inline = 0;
  }
  if (indent == null) {
    indent = 0;
  }
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectEncoder == null) {
    objectEncoder = null;
  }
  output = '';
  prefix = (indent ? Utils.strRepeat(' ', indent) : '');
  if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
    output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
  } else {
    if (input instanceof Array) {
      for (i = 0, len = input.length; i < len; i++) {
        value = input[i];
        willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
        output += prefix + '-' + (willBeInlined ? ' ' : "\n") + this.dump(value, inline - 1, (willBeInlined ? 0 : indent + this.
indentation), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
      }
    } else {
      for (key in input) {
        value = input[key];
        willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
        output += prefix + Inline.dump(key, exceptionOnInvalidType, objectEncoder) + ':' + (willBeInlined ? ' ' : "\n") + this.dump
(value, inline - 1, (willBeInlined ? 0 : indent + this.indentation), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
      }
    }
  }
  return output;
}
```
- example usage
```shell
...
}
if (objectEncoder == null) {
  objectEncoder = null;
}
output = '';
prefix = (indent ? Utils.strRepeat(' ', indent) : '');
if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
  output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
} else {
  if (input instanceof Array) {
    for (i = 0, len = input.length; i < len; i++) {
      value = input[i];
      willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
      output += prefix + '-' + (willBeInlined ? ' ' : "\n") + this.dump(value, inline - 1, (willBeInlined ? 0 : indent + this.indentation
), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
    }
...
```



# <a name="apidoc.module.yamljs.Escaper"></a>[module yamljs.Escaper](#apidoc.module.yamljs.Escaper)

#### <a name="apidoc.element.yamljs.Escaper.Escaper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Escaper ()](#apidoc.element.yamljs.Escaper.Escaper)
- description and source-code
```javascript
function Escaper() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Escaper.escapeWithDoubleQuotes"></a>[function <span class="apidocSignatureSpan">yamljs.Escaper.</span>escapeWithDoubleQuotes (value)](#apidoc.element.yamljs.Escaper.escapeWithDoubleQuotes)
- description and source-code
```javascript
escapeWithDoubleQuotes = function (value) {
  var result;
  result = this.PATTERN_MAPPING_ESCAPEES.replace(value, (function(_this) {
    return function(str) {
      return _this.MAPPING_ESCAPEES_TO_ESCAPED[str];
    };
  })(this));
  return '"' + result + '"';
}
```
- example usage
```shell
...
if (Utils.isNumeric(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseFloat(value)));
}
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
}
if (Escaper.requiresDoubleQuoting(value)) {
  return Escaper.escapeWithDoubleQuotes(value);
}
if (Escaper.requiresSingleQuoting(value)) {
  return Escaper.escapeWithSingleQuotes(value);
}
if ('' === value) {
  return '""';
}
...
```

#### <a name="apidoc.element.yamljs.Escaper.escapeWithSingleQuotes"></a>[function <span class="apidocSignatureSpan">yamljs.Escaper.</span>escapeWithSingleQuotes (value)](#apidoc.element.yamljs.Escaper.escapeWithSingleQuotes)
- description and source-code
```javascript
escapeWithSingleQuotes = function (value) {
  return "'" + value.replace(/'/g, "''") + "'";
}
```
- example usage
```shell
...
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
}
if (Escaper.requiresDoubleQuoting(value)) {
  return Escaper.escapeWithDoubleQuotes(value);
}
if (Escaper.requiresSingleQuoting(value)) {
  return Escaper.escapeWithSingleQuotes(value);
}
if ('' === value) {
  return '""';
}
if (Utils.PATTERN_DATE.test(value)) {
  return "'" + value + "'";
}
...
```

#### <a name="apidoc.element.yamljs.Escaper.requiresDoubleQuoting"></a>[function <span class="apidocSignatureSpan">yamljs.Escaper.</span>requiresDoubleQuoting (value)](#apidoc.element.yamljs.Escaper.requiresDoubleQuoting)
- description and source-code
```javascript
requiresDoubleQuoting = function (value) {
  return this.PATTERN_CHARACTERS_TO_ESCAPE.test(value);
}
```
- example usage
```shell
...
}
if (Utils.isNumeric(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseFloat(value)));
}
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
}
if (Escaper.requiresDoubleQuoting(value)) {
  return Escaper.escapeWithDoubleQuotes(value);
}
if (Escaper.requiresSingleQuoting(value)) {
  return Escaper.escapeWithSingleQuotes(value);
}
if ('' === value) {
  return '""';
...
```

#### <a name="apidoc.element.yamljs.Escaper.requiresSingleQuoting"></a>[function <span class="apidocSignatureSpan">yamljs.Escaper.</span>requiresSingleQuoting (value)](#apidoc.element.yamljs.Escaper.requiresSingleQuoting)
- description and source-code
```javascript
requiresSingleQuoting = function (value) {
  return this.PATTERN_SINGLE_QUOTING.test(value);
}
```
- example usage
```shell
...
}
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
}
if (Escaper.requiresDoubleQuoting(value)) {
  return Escaper.escapeWithDoubleQuotes(value);
}
if (Escaper.requiresSingleQuoting(value)) {
  return Escaper.escapeWithSingleQuotes(value);
}
if ('' === value) {
  return '""';
}
if (Utils.PATTERN_DATE.test(value)) {
  return "'" + value + "'";
...
```



# <a name="apidoc.module.yamljs.Inline"></a>[module yamljs.Inline](#apidoc.module.yamljs.Inline)

#### <a name="apidoc.element.yamljs.Inline.Inline"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Inline ()](#apidoc.element.yamljs.Inline.Inline)
- description and source-code
```javascript
function Inline() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Inline.configure"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>configure (exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Inline.configure)
- description and source-code
```javascript
configure = function (exceptionOnInvalidType, objectDecoder) {
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = null;
  }
  if (objectDecoder == null) {
    objectDecoder = null;
  }
  this.settings.exceptionOnInvalidType = exceptionOnInvalidType;
  this.settings.objectDecoder = objectDecoder;
}
```
- example usage
```shell
...
if (this.CONTEXT_SEQUENCE === context) {
  throw new ParseException('You cannot define a mapping item when in a sequence');
}
context = this.CONTEXT_MAPPING;
if (data == null) {
  data = {};
}
Inline.configure(exceptionOnInvalidType, objectDecoder);
try {
  key = Inline.parseScalar(values.key);
} catch (error) {
  e = error;
  e.parsedLine = this.getRealCurrentLineNb() + 1;
  e.snippet = this.currentLine;
  throw e;
...
```

#### <a name="apidoc.element.yamljs.Inline.dump"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>dump (value, exceptionOnInvalidType, objectEncoder)](#apidoc.element.yamljs.Inline.dump)
- description and source-code
```javascript
dump = function (value, exceptionOnInvalidType, objectEncoder) {
  var ref, result, type;
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectEncoder == null) {
    objectEncoder = null;
  }
  if (value == null) {
    return 'null';
  }
  type = typeof value;
  if (type === 'object') {
    if (value instanceof Date) {
      return value.toISOString();
    } else if (objectEncoder != null) {
      result = objectEncoder(value);
      if (typeof result === 'string' || (result != null)) {
        return result;
      }
    }
    return this.dumpObject(value);
  }
  if (type === 'boolean') {
    return (value ? 'true' : 'false');
  }
  if (Utils.isDigits(value)) {
    return (type === 'string' ? "'" + value + "'" : String(parseInt(value)));
  }
  if (Utils.isNumeric(value)) {
    return (type === 'string' ? "'" + value + "'" : String(parseFloat(value)));
  }
  if (type === 'number') {
    return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
  }
  if (Escaper.requiresDoubleQuoting(value)) {
    return Escaper.escapeWithDoubleQuotes(value);
  }
  if (Escaper.requiresSingleQuoting(value)) {
    return Escaper.escapeWithSingleQuotes(value);
  }
  if ('' === value) {
    return '""';
  }
  if (Utils.PATTERN_DATE.test(value)) {
    return "'" + value + "'";
  }
  if ((ref = value.toLowerCase()) === 'null' || ref === '~' || ref === 'true' || ref === 'false') {
    return "'" + value + "'";
  }
  return value;
}
```
- example usage
```shell
...
}
if (objectEncoder == null) {
  objectEncoder = null;
}
output = '';
prefix = (indent ? Utils.strRepeat(' ', indent) : '');
if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
  output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
} else {
  if (input instanceof Array) {
    for (i = 0, len = input.length; i < len; i++) {
      value = input[i];
      willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
      output += prefix + '-' + (willBeInlined ? ' ' : "\n") + this.dump(value, inline - 1, (willBeInlined ? 0 : indent + this.indentation
), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
    }
...
```

#### <a name="apidoc.element.yamljs.Inline.dumpObject"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>dumpObject (value, exceptionOnInvalidType, objectSupport)](#apidoc.element.yamljs.Inline.dumpObject)
- description and source-code
```javascript
dumpObject = function (value, exceptionOnInvalidType, objectSupport) {
  var j, key, len1, output, val;
  if (objectSupport == null) {
    objectSupport = null;
  }
  if (value instanceof Array) {
    output = [];
    for (j = 0, len1 = value.length; j < len1; j++) {
      val = value[j];
      output.push(this.dump(val));
    }
    return '[' + output.join(', ') + ']';
  } else {
    output = [];
    for (key in value) {
      val = value[key];
      output.push(this.dump(key) + ': ' + this.dump(val));
    }
    return '{' + output.join(', ') + '}';
  }
}
```
- example usage
```shell
...
    return value.toISOString();
  } else if (objectEncoder != null) {
    result = objectEncoder(value);
    if (typeof result === 'string' || (result != null)) {
      return result;
    }
  }
  return this.dumpObject(value);
}
if (type === 'boolean') {
  return (value ? 'true' : 'false');
}
if (Utils.isDigits(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseInt(value)));
}
...
```

#### <a name="apidoc.element.yamljs.Inline.evaluateScalar"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>evaluateScalar (scalar, context)](#apidoc.element.yamljs.Inline.evaluateScalar)
- description and source-code
```javascript
evaluateScalar = function (scalar, context) {
  var cast, date, exceptionOnInvalidType, firstChar, firstSpace, firstWord, objectDecoder, raw, scalarLower, subValue, trimmedScalar
;
  scalar = Utils.trim(scalar);
  scalarLower = scalar.toLowerCase();
  switch (scalarLower) {
    case 'null':
    case '':
    case '~':
      return null;
    case 'true':
      return true;
    case 'false':
      return false;
    case '.inf':
      return 2e308;
    case '.nan':
      return 0/0;
    case '-.inf':
      return 2e308;
    default:
      firstChar = scalarLower.charAt(0);
      switch (firstChar) {
        case '!':
          firstSpace = scalar.indexOf(' ');
          if (firstSpace === -1) {
            firstWord = scalarLower;
          } else {
            firstWord = scalarLower.slice(0, firstSpace);
          }
          switch (firstWord) {
            case '!':
              if (firstSpace !== -1) {
                return parseInt(this.parseScalar(scalar.slice(2)));
              }
              return null;
            case '!str':
              return Utils.ltrim(scalar.slice(4));
            case '!!str':
              return Utils.ltrim(scalar.slice(5));
            case '!!int':
              return parseInt(this.parseScalar(scalar.slice(5)));
            case '!!bool':
              return Utils.parseBoolean(this.parseScalar(scalar.slice(6)), false);
            case '!!float':
              return parseFloat(this.parseScalar(scalar.slice(7)));
            case '!!timestamp':
              return Utils.stringToDate(Utils.ltrim(scalar.slice(11)));
            default:
              if (context == null) {
                context = {
                  exceptionOnInvalidType: this.settings.exceptionOnInvalidType,
                  objectDecoder: this.settings.objectDecoder,
                  i: 0
                };
              }
              objectDecoder = context.objectDecoder, exceptionOnInvalidType = context.exceptionOnInvalidType;
              if (objectDecoder) {
                trimmedScalar = Utils.rtrim(scalar);
                firstSpace = trimmedScalar.indexOf(' ');
                if (firstSpace === -1) {
                  return objectDecoder(trimmedScalar, null);
                } else {
                  subValue = Utils.ltrim(trimmedScalar.slice(firstSpace + 1));
                  if (!(subValue.length > 0)) {
                    subValue = null;
                  }
                  return objectDecoder(trimmedScalar.slice(0, firstSpace), subValue);
                }
              }
              if (exceptionOnInvalidType) {
                throw new ParseException('Custom object support when parsing a YAML file has been disabled.');
              }
              return null;
          }
          break;
        case '0':
          if ('0x' === scalar.slice(0, 2)) {
            return Utils.hexDec(scalar);
          } else if (Utils.isDigits(scalar)) {
            return Utils.octDec(scalar);
          } else if (Utils.isNumeric(scalar)) {
            return parseFloat(scalar);
          } else {
            return scalar;
          }
          break;
        case '+':
          if (Utils.isDigits(scalar)) {
            raw = scalar;
            cast = parseInt(raw);
            if (raw === String(cast)) {
              return cast;
            } else {
              return raw;
            }
          } else if (Utils.isNumeric(scalar)) {
            return parseFloat(scalar);
          } else if (this.PATTERN_THOUSAND_NUMERIC_SCALAR.test(scalar)) {
            return parseFloat(scalar.replace(',', ''));
          }
          return scalar;
        case '-':
          if (Utils.isDigits(scalar.slice(1))) {
            if ('0' === scalar.charAt(1)) {
              return -Utils.octDec(scalar.slice(1));
            } else {
              raw = scalar.slice(1);
              cast = parseInt(raw);
              if (raw === String(cast)) {
                return -cast;
              } else {
                return -raw;
              }
            }
          } else if (Utils.isNumeric(scalar)) {
            retu ...
```
- example usage
```shell
...
        output = match[1];
        i += output.length;
      } else {
        throw new ParseException('Malformed inline YAML string (' + scalar + ').');
      }
    }
    if (evaluate) {
      output = this.evaluateScalar(output, context);
    }
  }
  context.i = i;
  return output;
};

Inline.parseQuotedScalar = function(scalar, context) {
...
```

#### <a name="apidoc.element.yamljs.Inline.parse"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>parse (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Inline.parse)
- description and source-code
```javascript
parse = function (value, exceptionOnInvalidType, objectDecoder) {
  var context, result;
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectDecoder == null) {
    objectDecoder = null;
  }
  this.settings.exceptionOnInvalidType = exceptionOnInvalidType;
  this.settings.objectDecoder = objectDecoder;
  if (value == null) {
    return '';
  }
  value = Utils.trim(value);
  if (0 === value.length) {
    return '';
  }
  context = {
    exceptionOnInvalidType: exceptionOnInvalidType,
    objectDecoder: objectDecoder,
    i: 0
  };
  switch (value.charAt(0)) {
    case '[':
      result = this.parseSequence(value, context);
      ++context.i;
      break;
    case '{':
      result = this.parseMapping(value, context);
      ++context.i;
      break;
    default:
      result = this.parseScalar(value, null, ['"', "'"], context);
  }
  if (this.PATTERN_TRAILING_COMMENTS.replace(value.slice(context.i), '') !== '') {
    throw new ParseException('Unexpected characters near "' + value.slice(context.i) + '".');
  }
  return result;
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

#### <a name="apidoc.element.yamljs.Inline.parseMapping"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseMapping (mapping, context)](#apidoc.element.yamljs.Inline.parseMapping)
- description and source-code
```javascript
parseMapping = function (mapping, context) {
  var done, i, key, len, output, shouldContinueWhileLoop, value;
  output = {};
  len = mapping.length;
  i = context.i;
  i += 1;
  shouldContinueWhileLoop = false;
  while (i < len) {
    context.i = i;
    switch (mapping.charAt(i)) {
      case ' ':
      case ',':
      case "\n":
        ++i;
        context.i = i;
        shouldContinueWhileLoop = true;
        break;
      case '}':
        return output;
    }
    if (shouldContinueWhileLoop) {
      shouldContinueWhileLoop = false;
      continue;
    }
    key = this.parseScalar(mapping, [':', ' ', "\n"], ['"', "'"], context, false);
    i = context.i;
    done = false;
    while (i < len) {
      context.i = i;
      switch (mapping.charAt(i)) {
        case '[':
          value = this.parseSequence(mapping, context);
          i = context.i;
          if (output[key] === void 0) {
            output[key] = value;
          }
          done = true;
          break;
        case '{':
          value = this.parseMapping(mapping, context);
          i = context.i;
          if (output[key] === void 0) {
            output[key] = value;
          }
          done = true;
          break;
        case ':':
        case ' ':
        case "\n":
          break;
        default:
          value = this.parseScalar(mapping, [',', '}'], ['"', "'"], context);
          i = context.i;
          if (output[key] === void 0) {
            output[key] = value;
          }
          done = true;
          --i;
      }
      ++i;
      if (done) {
        break;
      }
    }
  }
  throw new ParseMore('Malformed inline YAML string ' + mapping);
}
```
- example usage
```shell
...
};
switch (value.charAt(0)) {
  case '[':
    result = this.parseSequence(value, context);
    ++context.i;
    break;
  case '{':
    result = this.parseMapping(value, context);
    ++context.i;
    break;
  default:
    result = this.parseScalar(value, null, ['"', "'"], context);
}
if (this.PATTERN_TRAILING_COMMENTS.replace(value.slice(context.i), '') !== '') {
  throw new ParseException('Unexpected characters near "' + value.slice(context.i) + '".');
...
```

#### <a name="apidoc.element.yamljs.Inline.parseQuotedScalar"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseQuotedScalar (scalar, context)](#apidoc.element.yamljs.Inline.parseQuotedScalar)
- description and source-code
```javascript
parseQuotedScalar = function (scalar, context) {
  var i, match, output;
  i = context.i;
  if (!(match = this.PATTERN_QUOTED_SCALAR.exec(scalar.slice(i)))) {
    throw new ParseMore('Malformed inline YAML string (' + scalar.slice(i) + ').');
  }
  output = match[0].substr(1, match[0].length - 2);
  if ('"' === scalar.charAt(i)) {
    output = Unescaper.unescapeDoubleQuotedString(output);
  } else {
    output = Unescaper.unescapeSingleQuotedString(output);
  }
  i += match[0].length;
  context.i = i;
  return output;
}
```
- example usage
```shell
...
    exceptionOnInvalidType: this.settings.exceptionOnInvalidType,
    objectDecoder: this.settings.objectDecoder,
    i: 0
  };
}
i = context.i;
if (ref = scalar.charAt(i), indexOf.call(stringDelimiters, ref) >= 0) {
  output = this.parseQuotedScalar(scalar, context);
  i = context.i;
  if (delimiters != null) {
    tmp = Utils.ltrim(scalar.slice(i), ' ');
    if (!(ref1 = tmp.charAt(0), indexOf.call(delimiters, ref1) >= 0)) {
      throw new ParseException('Unexpected characters (' + scalar.slice(i) + ').');
    }
  }
...
```

#### <a name="apidoc.element.yamljs.Inline.parseScalar"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseScalar (scalar, delimiters, stringDelimiters, context, evaluate)](#apidoc.element.yamljs.Inline.parseScalar)
- description and source-code
```javascript
parseScalar = function (scalar, delimiters, stringDelimiters, context, evaluate) {
  var i, joinedDelimiters, match, output, pattern, ref, ref1, strpos, tmp;
  if (delimiters == null) {
    delimiters = null;
  }
  if (stringDelimiters == null) {
    stringDelimiters = ['"', "'"];
  }
  if (context == null) {
    context = null;
  }
  if (evaluate == null) {
    evaluate = true;
  }
  if (context == null) {
    context = {
      exceptionOnInvalidType: this.settings.exceptionOnInvalidType,
      objectDecoder: this.settings.objectDecoder,
      i: 0
    };
  }
  i = context.i;
  if (ref = scalar.charAt(i), indexOf.call(stringDelimiters, ref) >= 0) {
    output = this.parseQuotedScalar(scalar, context);
    i = context.i;
    if (delimiters != null) {
      tmp = Utils.ltrim(scalar.slice(i), ' ');
      if (!(ref1 = tmp.charAt(0), indexOf.call(delimiters, ref1) >= 0)) {
        throw new ParseException('Unexpected characters (' + scalar.slice(i) + ').');
      }
    }
  } else {
    if (!delimiters) {
      output = scalar.slice(i);
      i += output.length;
      strpos = output.indexOf(' #');
      if (strpos !== -1) {
        output = Utils.rtrim(output.slice(0, strpos));
      }
    } else {
      joinedDelimiters = delimiters.join('|');
      pattern = this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters];
      if (pattern == null) {
        pattern = new Pattern('^(.+?)(' + joinedDelimiters + ')');
        this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters] = pattern;
      }
      if (match = pattern.exec(scalar.slice(i))) {
        output = match[1];
        i += output.length;
      } else {
        throw new ParseException('Malformed inline YAML string (' + scalar + ').');
      }
    }
    if (evaluate) {
      output = this.evaluateScalar(output, context);
    }
  }
  context.i = i;
  return output;
}
```
- example usage
```shell
...
      ++context.i;
      break;
    case '{':
      result = this.parseMapping(value, context);
      ++context.i;
      break;
    default:
      result = this.parseScalar(value, null, ['"', "'"], context);
  }
  if (this.PATTERN_TRAILING_COMMENTS.replace(value.slice(context.i), '') !== '') {
    throw new ParseException('Unexpected characters near "' + value.slice(context.i) + '".');
  }
  return result;
};
...
```

#### <a name="apidoc.element.yamljs.Inline.parseSequence"></a>[function <span class="apidocSignatureSpan">yamljs.Inline.</span>parseSequence (sequence, context)](#apidoc.element.yamljs.Inline.parseSequence)
- description and source-code
```javascript
parseSequence = function (sequence, context) {
  var e, i, isQuoted, len, output, ref, value;
  output = [];
  len = sequence.length;
  i = context.i;
  i += 1;
  while (i < len) {
    context.i = i;
    switch (sequence.charAt(i)) {
      case '[':
        output.push(this.parseSequence(sequence, context));
        i = context.i;
        break;
      case '{':
        output.push(this.parseMapping(sequence, context));
        i = context.i;
        break;
      case ']':
        return output;
      case ',':
      case ' ':
      case "\n":
        break;
      default:
        isQuoted = ((ref = sequence.charAt(i)) === '"' || ref === "'");
        value = this.parseScalar(sequence, [',', ']'], ['"', "'"], context);
        i = context.i;
        if (!isQuoted && typeof value === 'string' && (value.indexOf(': ') !== -1 || value.indexOf(":\n") !== -1)) {
          try {
            value = this.parseMapping('{' + value + '}');
          } catch (error) {
            e = error;
          }
        }
        output.push(value);
        --i;
    }
    ++i;
  }
  throw new ParseMore('Malformed inline YAML string ' + sequence);
}
```
- example usage
```shell
...
context = {
  exceptionOnInvalidType: exceptionOnInvalidType,
  objectDecoder: objectDecoder,
  i: 0
};
switch (value.charAt(0)) {
  case '[':
    result = this.parseSequence(value, context);
    ++context.i;
    break;
  case '{':
    result = this.parseMapping(value, context);
    ++context.i;
    break;
  default:
...
```



# <a name="apidoc.module.yamljs.Parser"></a>[module yamljs.Parser](#apidoc.module.yamljs.Parser)

#### <a name="apidoc.element.yamljs.Parser.Parser"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Parser (offset)](#apidoc.element.yamljs.Parser.Parser)
- description and source-code
```javascript
function Parser(offset) {
  this.offset = offset != null ? offset : 0;
  this.lines = [];
  this.currentLineNb = -1;
  this.currentLine = '';
  this.refs = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.yamljs.Parser.prototype"></a>[module yamljs.Parser.prototype](#apidoc.module.yamljs.Parser.prototype)

#### <a name="apidoc.element.yamljs.Parser.prototype.cleanup"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>cleanup (value)](#apidoc.element.yamljs.Parser.prototype.cleanup)
- description and source-code
```javascript
cleanup = function (value) {
  var count, i, indent, j, l, len, len1, line, lines, ref, ref1, ref2, smallestIndent, trimmedValue;
  if (value.indexOf("\r") !== -1) {
    value = value.split("\r\n").join("\n").split("\r").join("\n");
  }
  count = 0;
  ref = this.PATTERN_YAML_HEADER.replaceAll(value, ''), value = ref[0], count = ref[1];
  this.offset += count;
  ref1 = this.PATTERN_LEADING_COMMENTS.replaceAll(value, '', 1), trimmedValue = ref1[0], count = ref1[1];
  if (count === 1) {
    this.offset += Utils.subStrCount(value, "\n") - Utils.subStrCount(trimmedValue, "\n");
    value = trimmedValue;
  }
  ref2 = this.PATTERN_DOCUMENT_MARKER_START.replaceAll(value, '', 1), trimmedValue = ref2[0], count = ref2[1];
  if (count === 1) {
    this.offset += Utils.subStrCount(value, "\n") - Utils.subStrCount(trimmedValue, "\n");
    value = trimmedValue;
    value = this.PATTERN_DOCUMENT_MARKER_END.replace(value, '');
  }
  lines = value.split("\n");
  smallestIndent = -1;
  for (j = 0, len = lines.length; j < len; j++) {
    line = lines[j];
    if (Utils.trim(line, ' ').length === 0) {
      continue;
    }
    indent = line.length - Utils.ltrim(line).length;
    if (smallestIndent === -1 || indent < smallestIndent) {
      smallestIndent = indent;
    }
  }
  if (smallestIndent > 0) {
    for (i = l = 0, len1 = lines.length; l < len1; i = ++l) {
      line = lines[i];
      lines[i] = line.slice(smallestIndent);
    }
    value = lines.join("\n");
  }
  return value;
}
```
- example usage
```shell
...
  exceptionOnInvalidType = false;
}
if (objectDecoder == null) {
  objectDecoder = null;
}
this.currentLineNb = -1;
this.currentLine = '';
this.lines = this.cleanup(value).split("\n");
data = null;
context = this.CONTEXT_NONE;
allowOverwrite = false;
while (this.moveToNextLine()) {
  if (this.isCurrentLineEmpty()) {
    continue;
  }
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.getCurrentLineIndentation"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getCurrentLineIndentation ()](#apidoc.element.yamljs.Parser.prototype.getCurrentLineIndentation)
- description and source-code
```javascript
getCurrentLineIndentation = function () {
  return this.currentLine.length - Utils.ltrim(this.currentLine, ' ').length;
}
```
- example usage
```shell
...
  }
} else {
  if (((ref = values.leadspaces) != null ? ref.length : void 0) && (matches = this.PATTERN_COMPACT_NOTATION.exec(values.value))) {
    c = this.getRealCurrentLineNb();
    parser = new Parser(c);
    parser.refs = this.refs;
    block = values.value;
    indent = this.getCurrentLineIndentation();
    if (this.isNextLineIndented(false)) {
      block += "\n" + this.getNextEmbedBlock(indent + values.leadspaces.length + 1, true);
    }
    data.push(parser.parse(block, exceptionOnInvalidType, objectDecoder));
  } else {
    data.push(this.parseValue(values.value, exceptionOnInvalidType, objectDecoder));
  }
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.getNextEmbedBlock"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getNextEmbedBlock (indentation, includeUnindentedCollection)](#apidoc.element.yamljs.Parser.prototype.getNextEmbedBlock)
- description and source-code
```javascript
getNextEmbedBlock = function (indentation, includeUnindentedCollection) {
  var data, indent, isItUnindentedCollection, newIndent, removeComments, removeCommentsPattern, unindentedEmbedBlock;
  if (indentation == null) {
    indentation = null;
  }
  if (includeUnindentedCollection == null) {
    includeUnindentedCollection = false;
  }
  this.moveToNextLine();
  if (indentation == null) {
    newIndent = this.getCurrentLineIndentation();
    unindentedEmbedBlock = this.isStringUnIndentedCollectionItem(this.currentLine);
    if (!(this.isCurrentLineEmpty()) && 0 === newIndent && !unindentedEmbedBlock) {
      throw new ParseException('Indentation problem.', this.getRealCurrentLineNb() + 1, this.currentLine);
    }
  } else {
    newIndent = indentation;
  }
  data = [this.currentLine.slice(newIndent)];
  if (!includeUnindentedCollection) {
    isItUnindentedCollection = this.isStringUnIndentedCollectionItem(this.currentLine);
  }
  removeCommentsPattern = this.PATTERN_FOLDED_SCALAR_END;
  removeComments = !removeCommentsPattern.test(this.currentLine);
  while (this.moveToNextLine()) {
    indent = this.getCurrentLineIndentation();
    if (indent === newIndent) {
      removeComments = !removeCommentsPattern.test(this.currentLine);
    }
    if (removeComments && this.isCurrentLineComment()) {
      continue;
    }
    if (this.isCurrentLineBlank()) {
      data.push(this.currentLine.slice(newIndent));
      continue;
    }
    if (isItUnindentedCollection && !this.isStringUnIndentedCollectionItem(this.currentLine) && indent === newIndent) {
      this.moveToPreviousLine();
      break;
    }
    if (indent >= newIndent) {
      data.push(this.currentLine.slice(newIndent));
    } else if (Utils.ltrim(this.currentLine).charAt(0) === '#') {

    } else if (0 === indent) {
      this.moveToPreviousLine();
      break;
    } else {
      throw new ParseException('Indentation problem.', this.getRealCurrentLineNb() + 1, this.currentLine);
    }
  }
  return data.join("\n");
}
```
- example usage
```shell
...
  values.value = matches.value;
}
if (!(values.value != null) || '' === Utils.trim(values.value, ' ') || Utils.ltrim(values.value, ' ').indexOf('#') === 0) {
  if (this.currentLineNb < this.lines.length - 1 && !this.isNextLineUnIndentedCollection()) {
    c = this.getRealCurrentLineNb() + 1;
    parser = new Parser(c);
    parser.refs = this.refs;
    data.push(parser.parse(this.getNextEmbedBlock(null, true), exceptionOnInvalidType, objectDecoder));
  } else {
    data.push(null);
  }
} else {
  if (((ref = values.leadspaces) != null ? ref.length : void 0) && (matches = this.PATTERN_COMPACT_NOTATION.exec(values.value))) {
    c = this.getRealCurrentLineNb();
    parser = new Parser(c);
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.getRealCurrentLineNb"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>getRealCurrentLineNb ()](#apidoc.element.yamljs.Parser.prototype.getRealCurrentLineNb)
- description and source-code
```javascript
getRealCurrentLineNb = function () {
  return this.currentLineNb + this.offset;
}
```
- example usage
```shell
...
context = this.CONTEXT_NONE;
allowOverwrite = false;
while (this.moveToNextLine()) {
  if (this.isCurrentLineEmpty()) {
    continue;
  }
  if ("\t" === this.currentLine[0]) {
    throw new ParseException('A YAML file cannot contain tabs as indentation.', this.getRealCurrentLineNb() + 1, this.currentLine
);
  }
  isRef = mergeNode = false;
  if (values = this.PATTERN_SEQUENCE_ITEM.exec(this.currentLine)) {
    if (this.CONTEXT_MAPPING === context) {
      throw new ParseException('You cannot define a sequence item when in a mapping');
    }
    context = this.CONTEXT_SEQUENCE;
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isCurrentLineBlank"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineBlank ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineBlank)
- description and source-code
```javascript
isCurrentLineBlank = function () {
  return '' === Utils.trim(this.currentLine, ' ');
}
```
- example usage
```shell
...
indent = this.getCurrentLineIndentation();
if (indent === newIndent) {
  removeComments = !removeCommentsPattern.test(this.currentLine);
}
if (removeComments && this.isCurrentLineComment()) {
  continue;
}
if (this.isCurrentLineBlank()) {
  data.push(this.currentLine.slice(newIndent));
  continue;
}
if (isItUnindentedCollection && !this.isStringUnIndentedCollectionItem(this.currentLine) && indent === newIndent) {
  this.moveToPreviousLine();
  break;
}
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isCurrentLineComment"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineComment ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineComment)
- description and source-code
```javascript
isCurrentLineComment = function () {
  var ltrimmedLine;
  ltrimmedLine = Utils.ltrim(this.currentLine, ' ');
  return ltrimmedLine.charAt(0) === '#';
}
```
- example usage
```shell
...
removeCommentsPattern = this.PATTERN_FOLDED_SCALAR_END;
removeComments = !removeCommentsPattern.test(this.currentLine);
while (this.moveToNextLine()) {
  indent = this.getCurrentLineIndentation();
  if (indent === newIndent) {
    removeComments = !removeCommentsPattern.test(this.currentLine);
  }
  if (removeComments && this.isCurrentLineComment()) {
    continue;
  }
  if (this.isCurrentLineBlank()) {
    data.push(this.currentLine.slice(newIndent));
    continue;
  }
  if (isItUnindentedCollection && !this.isStringUnIndentedCollectionItem(this.currentLine) && indent === newIndent) {
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isCurrentLineEmpty"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isCurrentLineEmpty ()](#apidoc.element.yamljs.Parser.prototype.isCurrentLineEmpty)
- description and source-code
```javascript
isCurrentLineEmpty = function () {
  var trimmedLine;
  trimmedLine = Utils.trim(this.currentLine, ' ');
  return trimmedLine.length === 0 || trimmedLine.charAt(0) === '#';
}
```
- example usage
```shell
...
this.currentLineNb = -1;
this.currentLine = '';
this.lines = this.cleanup(value).split("\n");
data = null;
context = this.CONTEXT_NONE;
allowOverwrite = false;
while (this.moveToNextLine()) {
  if (this.isCurrentLineEmpty()) {
    continue;
  }
  if ("\t" === this.currentLine[0]) {
    throw new ParseException('A YAML file cannot contain tabs as indentation.', this.getRealCurrentLineNb() + 1, this.currentLine
);
  }
  isRef = mergeNode = false;
  if (values = this.PATTERN_SEQUENCE_ITEM.exec(this.currentLine)) {
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isNextLineIndented"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isNextLineIndented (ignoreComments)](#apidoc.element.yamljs.Parser.prototype.isNextLineIndented)
- description and source-code
```javascript
isNextLineIndented = function (ignoreComments) {
  var EOF, currentIndentation, ret;
  if (ignoreComments == null) {
    ignoreComments = true;
  }
  currentIndentation = this.getCurrentLineIndentation();
  EOF = !this.moveToNextLine();
  if (ignoreComments) {
    while (!EOF && this.isCurrentLineEmpty()) {
      EOF = !this.moveToNextLine();
    }
  } else {
    while (!EOF && this.isCurrentLineBlank()) {
      EOF = !this.moveToNextLine();
    }
  }
  if (EOF) {
    return false;
  }
  ret = false;
  if (this.getCurrentLineIndentation() > currentIndentation) {
    ret = true;
  }
  this.moveToPreviousLine();
  return ret;
}
```
- example usage
```shell
...
} else {
  if (((ref = values.leadspaces) != null ? ref.length : void 0) && (matches = this.PATTERN_COMPACT_NOTATION.exec(values.value))) {
    c = this.getRealCurrentLineNb();
    parser = new Parser(c);
    parser.refs = this.refs;
    block = values.value;
    indent = this.getCurrentLineIndentation();
    if (this.isNextLineIndented(false)) {
      block += "\n" + this.getNextEmbedBlock(indent + values.leadspaces.length + 1, true);
    }
    data.push(parser.parse(block, exceptionOnInvalidType, objectDecoder));
  } else {
    data.push(this.parseValue(values.value, exceptionOnInvalidType, objectDecoder));
  }
}
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isNextLineUnIndentedCollection"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isNextLineUnIndentedCollection (currentIndentation)](#apidoc.element.yamljs.Parser.prototype.isNextLineUnIndentedCollection)
- description and source-code
```javascript
isNextLineUnIndentedCollection = function (currentIndentation) {
  var notEOF, ret;
  if (currentIndentation == null) {
    currentIndentation = null;
  }
  if (currentIndentation == null) {
    currentIndentation = this.getCurrentLineIndentation();
  }
  notEOF = this.moveToNextLine();
  while (notEOF && this.isCurrentLineEmpty()) {
    notEOF = this.moveToNextLine();
  }
  if (false === notEOF) {
    return false;
  }
  ret = false;
  if (this.getCurrentLineIndentation() === currentIndentation && this.isStringUnIndentedCollectionItem(this.currentLine)) {
    ret = true;
  }
  this.moveToPreviousLine();
  return ret;
}
```
- example usage
```shell
...
  data = [];
}
if ((values.value != null) && (matches = this.PATTERN_ANCHOR_VALUE.exec(values.value))) {
  isRef = matches.ref;
  values.value = matches.value;
}
if (!(values.value != null) || '' === Utils.trim(values.value, ' ') || Utils.ltrim(values.value, ' ').indexOf('#') === 0) {
  if (this.currentLineNb < this.lines.length - 1 && !this.isNextLineUnIndentedCollection()) {
    c = this.getRealCurrentLineNb() + 1;
    parser = new Parser(c);
    parser.refs = this.refs;
    data.push(parser.parse(this.getNextEmbedBlock(null, true), exceptionOnInvalidType, objectDecoder));
  } else {
    data.push(null);
  }
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.isStringUnIndentedCollectionItem"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>isStringUnIndentedCollectionItem ()](#apidoc.element.yamljs.Parser.prototype.isStringUnIndentedCollectionItem)
- description and source-code
```javascript
isStringUnIndentedCollectionItem = function () {
  return this.currentLine === '-' || this.currentLine.slice(0, 2) === '- ';
}
```
- example usage
```shell
...
}
if (includeUnindentedCollection == null) {
  includeUnindentedCollection = false;
}
this.moveToNextLine();
if (indentation == null) {
  newIndent = this.getCurrentLineIndentation();
  unindentedEmbedBlock = this.isStringUnIndentedCollectionItem(this.currentLine);
  if (!(this.isCurrentLineEmpty()) && 0 === newIndent && !unindentedEmbedBlock) {
    throw new ParseException('Indentation problem.', this.getRealCurrentLineNb() + 1, this.currentLine);
  }
} else {
  newIndent = indentation;
}
data = [this.currentLine.slice(newIndent)];
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.moveToNextLine"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>moveToNextLine ()](#apidoc.element.yamljs.Parser.prototype.moveToNextLine)
- description and source-code
```javascript
moveToNextLine = function () {
  if (this.currentLineNb >= this.lines.length - 1) {
    return false;
  }
  this.currentLine = this.lines[++this.currentLineNb];
  return true;
}
```
- example usage
```shell
...
}
this.currentLineNb = -1;
this.currentLine = '';
this.lines = this.cleanup(value).split("\n");
data = null;
context = this.CONTEXT_NONE;
allowOverwrite = false;
while (this.moveToNextLine()) {
  if (this.isCurrentLineEmpty()) {
    continue;
  }
  if ("\t" === this.currentLine[0]) {
    throw new ParseException('A YAML file cannot contain tabs as indentation.', this.getRealCurrentLineNb() + 1, this.currentLine
);
  }
  isRef = mergeNode = false;
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.moveToPreviousLine"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>moveToPreviousLine ()](#apidoc.element.yamljs.Parser.prototype.moveToPreviousLine)
- description and source-code
```javascript
moveToPreviousLine = function () {
  this.currentLine = this.lines[--this.currentLineNb];
}
```
- example usage
```shell
...
  continue;
}
if (this.isCurrentLineBlank()) {
  data.push(this.currentLine.slice(newIndent));
  continue;
}
if (isItUnindentedCollection && !this.isStringUnIndentedCollectionItem(this.currentLine) && indent === newIndent) {
  this.moveToPreviousLine();
  break;
}
if (indent >= newIndent) {
  data.push(this.currentLine.slice(newIndent));
} else if (Utils.ltrim(this.currentLine).charAt(0) === '#') {

} else if (0 === indent) {
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.parse"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parse (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Parser.prototype.parse)
- description and source-code
```javascript
parse = function (value, exceptionOnInvalidType, objectDecoder) {
  var alias, allowOverwrite, block, c, context, data, e, first, i, indent, isRef, j, k, key, l, lastKey, len, len1, len2, len3,
lineCount, m, matches, mergeNode, n, name, parsed, parsedItem, parser, ref, ref1, ref2, refName, refValue, val, values;
  if (exceptionOnInvalidType == null) {
    exceptionOnInvalidType = false;
  }
  if (objectDecoder == null) {
    objectDecoder = null;
  }
  this.currentLineNb = -1;
  this.currentLine = '';
  this.lines = this.cleanup(value).split("\n");
  data = null;
  context = this.CONTEXT_NONE;
  allowOverwrite = false;
  while (this.moveToNextLine()) {
    if (this.isCurrentLineEmpty()) {
      continue;
    }
    if ("\t" === this.currentLine[0]) {
      throw new ParseException('A YAML file cannot contain tabs as indentation.', this.getRealCurrentLineNb() + 1, this.currentLine
);
    }
    isRef = mergeNode = false;
    if (values = this.PATTERN_SEQUENCE_ITEM.exec(this.currentLine)) {
      if (this.CONTEXT_MAPPING === context) {
        throw new ParseException('You cannot define a sequence item when in a mapping');
      }
      context = this.CONTEXT_SEQUENCE;
      if (data == null) {
        data = [];
      }
      if ((values.value != null) && (matches = this.PATTERN_ANCHOR_VALUE.exec(values.value))) {
        isRef = matches.ref;
        values.value = matches.value;
      }
      if (!(values.value != null) || '' === Utils.trim(values.value, ' ') || Utils.ltrim(values.value, ' ').indexOf('#') === 0) {
        if (this.currentLineNb < this.lines.length - 1 && !this.isNextLineUnIndentedCollection()) {
          c = this.getRealCurrentLineNb() + 1;
          parser = new Parser(c);
          parser.refs = this.refs;
          data.push(parser.parse(this.getNextEmbedBlock(null, true), exceptionOnInvalidType, objectDecoder));
        } else {
          data.push(null);
        }
      } else {
        if (((ref = values.leadspaces) != null ? ref.length : void 0) && (matches = this.PATTERN_COMPACT_NOTATION.exec(values.value
))) {
          c = this.getRealCurrentLineNb();
          parser = new Parser(c);
          parser.refs = this.refs;
          block = values.value;
          indent = this.getCurrentLineIndentation();
          if (this.isNextLineIndented(false)) {
            block += "\n" + this.getNextEmbedBlock(indent + values.leadspaces.length + 1, true);
          }
          data.push(parser.parse(block, exceptionOnInvalidType, objectDecoder));
        } else {
          data.push(this.parseValue(values.value, exceptionOnInvalidType, objectDecoder));
        }
      }
    } else if ((values = this.PATTERN_MAPPING_ITEM.exec(this.currentLine)) && values.key.indexOf(' #') === -1) {
      if (this.CONTEXT_SEQUENCE === context) {
        throw new ParseException('You cannot define a mapping item when in a sequence');
      }
      context = this.CONTEXT_MAPPING;
      if (data == null) {
        data = {};
      }
      Inline.configure(exceptionOnInvalidType, objectDecoder);
      try {
        key = Inline.parseScalar(values.key);
      } catch (error) {
        e = error;
        e.parsedLine = this.getRealCurrentLineNb() + 1;
        e.snippet = this.currentLine;
        throw e;
      }
      if ('<<' === key) {
        mergeNode = true;
        allowOverwrite = true;
        if (((ref1 = values.value) != null ? ref1.indexOf('*') : void 0) === 0) {
          refName = values.value.slice(1);
          if (this.refs[refName] == null) {
            throw new ParseException('Reference "' + refName + '" does not exist.', this.getRealCurrentLineNb() + 1, this.currentLine
);
          }
          refValue = this.refs[refName];
          if (typeof refValue !== 'object') {
            throw new ParseException('YAML merge keys used with a scalar value instead of an object.', this.getRealCurrentLineNb
() + 1, this.currentLine);
          }
          if (refValue instanceof Array) {
            for (i = j = 0, len = refValue.length; j < len; i = ++j) {
              value = refValue[i];
              if (data[name = Strin ...
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

#### <a name="apidoc.element.yamljs.Parser.prototype.parseFoldedScalar"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parseFoldedScalar (separator, indicator, indentation)](#apidoc.element.yamljs.Parser.prototype.parseFoldedScalar)
- description and source-code
```javascript
parseFoldedScalar = function (separator, indicator, indentation) {
  var isCurrentLineBlank, j, len, line, matches, newText, notEOF, pattern, ref, text;
  if (indicator == null) {
    indicator = '';
  }
  if (indentation == null) {
    indentation = 0;
  }
  notEOF = this.moveToNextLine();
  if (!notEOF) {
    return '';
  }
  isCurrentLineBlank = this.isCurrentLineBlank();
  text = '';
  while (notEOF && isCurrentLineBlank) {
    if (notEOF = this.moveToNextLine()) {
      text += "\n";
      isCurrentLineBlank = this.isCurrentLineBlank();
    }
  }
  if (0 === indentation) {
    if (matches = this.PATTERN_INDENT_SPACES.exec(this.currentLine)) {
      indentation = matches[0].length;
    }
  }
  if (indentation > 0) {
    pattern = this.PATTERN_FOLDED_SCALAR_BY_INDENTATION[indentation];
    if (pattern == null) {
      pattern = new Pattern('^ {' + indentation + '}(.*)$');
      Parser.prototype.PATTERN_FOLDED_SCALAR_BY_INDENTATION[indentation] = pattern;
    }
    while (notEOF && (isCurrentLineBlank || (matches = pattern.exec(this.currentLine)))) {
      if (isCurrentLineBlank) {
        text += this.currentLine.slice(indentation);
      } else {
        text += matches[1];
      }
      if (notEOF = this.moveToNextLine()) {
        text += "\n";
        isCurrentLineBlank = this.isCurrentLineBlank();
      }
    }
  } else if (notEOF) {
    text += "\n";
  }
  if (notEOF) {
    this.moveToPreviousLine();
  }
  if ('>' === separator) {
    newText = '';
    ref = text.split("\n");
    for (j = 0, len = ref.length; j < len; j++) {
      line = ref[j];
      if (line.length === 0 || line.charAt(0) === ' ') {
        newText = Utils.rtrim(newText, ' ') + line + "\n";
      } else {
        newText += line + ' ';
      }
    }
    text = newText;
  }
  if ('+' !== indicator) {
    text = Utils.rtrim(text);
  }
  if ('' === indicator) {
    text = this.PATTERN_TRAILING_LINES.replace(text, "\n");
  } else if ('-' === indicator) {
    text = this.PATTERN_TRAILING_LINES.replace(text, '');
  }
  return text;
}
```
- example usage
```shell
...
}
if (matches = this.PATTERN_FOLDED_SCALAR_ALL.exec(value)) {
  modifiers = (ref = matches.modifiers) != null ? ref : '';
  foldedIndent = Math.abs(parseInt(modifiers));
  if (isNaN(foldedIndent)) {
    foldedIndent = 0;
  }
  val = this.parseFoldedScalar(matches.separator, this.PATTERN_DECIMAL.replace(modifiers, ''), foldedIndent);
  if (matches.type != null) {
    Inline.configure(exceptionOnInvalidType, objectDecoder);
    return Inline.parseScalar(matches.type + ' ' + val);
  } else {
    return val;
  }
}
...
```

#### <a name="apidoc.element.yamljs.Parser.prototype.parseValue"></a>[function <span class="apidocSignatureSpan">yamljs.Parser.prototype.</span>parseValue (value, exceptionOnInvalidType, objectDecoder)](#apidoc.element.yamljs.Parser.prototype.parseValue)
- description and source-code
```javascript
parseValue = function (value, exceptionOnInvalidType, objectDecoder) {
  var e, foldedIndent, matches, modifiers, pos, ref, ref1, val;
  if (0 === value.indexOf('*')) {
    pos = value.indexOf('#');
    if (pos !== -1) {
      value = value.substr(1, pos - 2);
    } else {
      value = value.slice(1);
    }
    if (this.refs[value] === void 0) {
      throw new ParseException('Reference "' + value + '" does not exist.', this.currentLine);
    }
    return this.refs[value];
  }
  if (matches = this.PATTERN_FOLDED_SCALAR_ALL.exec(value)) {
    modifiers = (ref = matches.modifiers) != null ? ref : '';
    foldedIndent = Math.abs(parseInt(modifiers));
    if (isNaN(foldedIndent)) {
      foldedIndent = 0;
    }
    val = this.parseFoldedScalar(matches.separator, this.PATTERN_DECIMAL.replace(modifiers, ''), foldedIndent);
    if (matches.type != null) {
      Inline.configure(exceptionOnInvalidType, objectDecoder);
      return Inline.parseScalar(matches.type + ' ' + val);
    } else {
      return val;
    }
  }
  if ((ref1 = value.charAt(0)) === '[' || ref1 === '{' || ref1 === '"' || ref1 === "'") {
    while (true) {
      try {
        return Inline.parse(value, exceptionOnInvalidType, objectDecoder);
      } catch (error) {
        e = error;
        if (e instanceof ParseMore && this.moveToNextLine()) {
          value += "\n" + Utils.trim(this.currentLine, ' ');
        } else {
          e.parsedLine = this.getRealCurrentLineNb() + 1;
          e.snippet = this.currentLine;
          throw e;
        }
      }
    }
  } else {
    if (this.isNextLineIndented()) {
      value += "\n" + this.getNextEmbedBlock();
    }
    return Inline.parse(value, exceptionOnInvalidType, objectDecoder);
  }
}
```
- example usage
```shell
...
      block = values.value;
      indent = this.getCurrentLineIndentation();
      if (this.isNextLineIndented(false)) {
        block += "\n" + this.getNextEmbedBlock(indent + values.leadspaces.length + 1, true);
      }
      data.push(parser.parse(block, exceptionOnInvalidType, objectDecoder));
    } else {
      data.push(this.parseValue(values.value, exceptionOnInvalidType, objectDecoder));
    }
  }
} else if ((values = this.PATTERN_MAPPING_ITEM.exec(this.currentLine)) && values.key.indexOf(' #') === -1) {
  if (this.CONTEXT_SEQUENCE === context) {
    throw new ParseException('You cannot define a mapping item when in a sequence');
  }
  context = this.CONTEXT_MAPPING;
...
```



# <a name="apidoc.module.yamljs.Pattern"></a>[module yamljs.Pattern](#apidoc.module.yamljs.Pattern)

#### <a name="apidoc.element.yamljs.Pattern.Pattern"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Pattern (rawRegex, modifiers)](#apidoc.element.yamljs.Pattern.Pattern)
- description and source-code
```javascript
function Pattern(rawRegex, modifiers) {
  var _char, capturingBracketNumber, cleanedRegex, i, len, mapping, name, part, subChar;
  if (modifiers == null) {
    modifiers = '';
  }
  cleanedRegex = '';
  len = rawRegex.length;
  mapping = null;
  capturingBracketNumber = 0;
  i = 0;
  while (i < len) {
    _char = rawRegex.charAt(i);
    if (_char === '\\') {
      cleanedRegex += rawRegex.slice(i, +(i + 1) + 1 || 9e9);
      i++;
    } else if (_char === '(') {
      if (i < len - 2) {
        part = rawRegex.slice(i, +(i + 2) + 1 || 9e9);
        if (part === '(?:') {
          i += 2;
          cleanedRegex += part;
        } else if (part === '(?<') {
          capturingBracketNumber++;
          i += 2;
          name = '';
          while (i + 1 < len) {
            subChar = rawRegex.charAt(i + 1);
            if (subChar === '>') {
              cleanedRegex += '(';
              i++;
              if (name.length > 0) {
                if (mapping == null) {
                  mapping = {};
                }
                mapping[name] = capturingBracketNumber;
              }
              break;
            } else {
              name += subChar;
            }
            i++;
          }
        } else {
          cleanedRegex += _char;
          capturingBracketNumber++;
        }
      } else {
        cleanedRegex += _char;
      }
    } else {
      cleanedRegex += _char;
    }
    i++;
  }
  this.rawRegex = rawRegex;
  this.cleanedRegex = cleanedRegex;
  this.regex = new RegExp(this.cleanedRegex, 'g' + modifiers.replace('g', ''));
  this.mapping = mapping;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.yamljs.Pattern.prototype"></a>[module yamljs.Pattern.prototype](#apidoc.module.yamljs.Pattern.prototype)

#### <a name="apidoc.element.yamljs.Pattern.prototype.exec"></a>[function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>exec (str)](#apidoc.element.yamljs.Pattern.prototype.exec)
- description and source-code
```javascript
exec = function (str) {
  var index, matches, name, ref;
  this.regex.lastIndex = 0;
  matches = this.regex.exec(str);
  if (matches == null) {
    return null;
  }
  if (this.mapping != null) {
    ref = this.mapping;
    for (name in ref) {
      index = ref[name];
      matches[name] = matches[index];
    }
  }
  return matches;
}
```
- example usage
```shell
...
} else {
  joinedDelimiters = delimiters.join('|');
  pattern = this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters];
  if (pattern == null) {
    pattern = new Pattern('^(.+?)(' + joinedDelimiters + ')');
    this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters] = pattern;
  }
  if (match = pattern.exec(scalar.slice(i))) {
    output = match[1];
    i += output.length;
  } else {
    throw new ParseException('Malformed inline YAML string (' + scalar + ').');
  }
}
if (evaluate) {
...
```

#### <a name="apidoc.element.yamljs.Pattern.prototype.replace"></a>[function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>replace (str, replacement)](#apidoc.element.yamljs.Pattern.prototype.replace)
- description and source-code
```javascript
replace = function (str, replacement) {
  this.regex.lastIndex = 0;
  return str.replace(this.regex, replacement);
}
```
- example usage
```shell
...

Escaper.requiresDoubleQuoting = function(value) {
  return this.PATTERN_CHARACTERS_TO_ESCAPE.test(value);
};

Escaper.escapeWithDoubleQuotes = function(value) {
  var result;
  result = this.PATTERN_MAPPING_ESCAPEES.replace(value, (function(_this) {
    return function(str) {
      return _this.MAPPING_ESCAPEES_TO_ESCAPED[str];
    };
  })(this));
  return '"' + result + '"';
};
...
```

#### <a name="apidoc.element.yamljs.Pattern.prototype.replaceAll"></a>[function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>replaceAll (str, replacement, limit)](#apidoc.element.yamljs.Pattern.prototype.replaceAll)
- description and source-code
```javascript
replaceAll = function (str, replacement, limit) {
  var count;
  if (limit == null) {
    limit = 0;
  }
  this.regex.lastIndex = 0;
  count = 0;
  while (this.regex.test(str) && (limit === 0 || count < limit)) {
    this.regex.lastIndex = 0;
    str = str.replace(this.regex, replacement);
    count++;
  }
  return [str, count];
}
```
- example usage
```shell
...

  Parser.prototype.cleanup = function(value) {
var count, i, indent, j, l, len, len1, line, lines, ref, ref1, ref2, smallestIndent, trimmedValue;
if (value.indexOf("\r") !== -1) {
  value = value.split("\r\n").join("\n").split("\r").join("\n");
}
count = 0;
ref = this.PATTERN_YAML_HEADER.replaceAll(value, ''), value = ref[0], count = ref[1];
this.offset += count;
ref1 = this.PATTERN_LEADING_COMMENTS.replaceAll(value, '', 1), trimmedValue = ref1[0], count = ref1[1];
if (count === 1) {
  this.offset += Utils.subStrCount(value, "\n") - Utils.subStrCount(trimmedValue, "\n");
  value = trimmedValue;
}
ref2 = this.PATTERN_DOCUMENT_MARKER_START.replaceAll(value, '', 1), trimmedValue = ref2[0], count = ref2[1];
...
```

#### <a name="apidoc.element.yamljs.Pattern.prototype.test"></a>[function <span class="apidocSignatureSpan">yamljs.Pattern.prototype.</span>test (str)](#apidoc.element.yamljs.Pattern.prototype.test)
- description and source-code
```javascript
test = function (str) {
  this.regex.lastIndex = 0;
  return this.regex.test(str);
}
```
- example usage
```shell
...
Escaper.PATTERN_CHARACTERS_TO_ESCAPE = new Pattern('[\\x00-\\x1f]|\xc2\x85|\xc2\xa0|\xe2\x80\xa8|\xe2\x80\xa9');

Escaper.PATTERN_MAPPING_ESCAPEES = new Pattern(Escaper.LIST_ESCAPEES.join('|').split('\\').join('\\\\'));

Escaper.PATTERN_SINGLE_QUOTING = new Pattern('[\\s\'":{}[\\],&*#?]|^[-?|<>=!%@']');

Escaper.requiresDoubleQuoting = function(value) {
  return this.PATTERN_CHARACTERS_TO_ESCAPE.test(value);
};

Escaper.escapeWithDoubleQuotes = function(value) {
  var result;
  result = this.PATTERN_MAPPING_ESCAPEES.replace(value, (function(_this) {
    return function(str) {
      return _this.MAPPING_ESCAPEES_TO_ESCAPED[str];
...
```



# <a name="apidoc.module.yamljs.Unescaper"></a>[module yamljs.Unescaper](#apidoc.module.yamljs.Unescaper)

#### <a name="apidoc.element.yamljs.Unescaper.Unescaper"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Unescaper ()](#apidoc.element.yamljs.Unescaper.Unescaper)
- description and source-code
```javascript
function Unescaper() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Unescaper.unescapeCharacter"></a>[function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeCharacter (value)](#apidoc.element.yamljs.Unescaper.unescapeCharacter)
- description and source-code
```javascript
unescapeCharacter = function (value) {
  var ch;
  ch = String.fromCharCode;
  switch (value.charAt(1)) {
    case '0':
      return ch(0);
    case 'a':
      return ch(7);
    case 'b':
      return ch(8);
    case 't':
      return "\t";
    case "\t":
      return "\t";
    case 'n':
      return "\n";
    case 'v':
      return ch(11);
    case 'f':
      return ch(12);
    case 'r':
      return ch(13);
    case 'e':
      return ch(27);
    case ' ':
      return ' ';
    case '"':
      return '"';
    case '/':
      return '/';
    case '\\':
      return '\\';
    case 'N':
      return ch(0x0085);
    case '_':
      return ch(0x00A0);
    case 'L':
      return ch(0x2028);
    case 'P':
      return ch(0x2029);
    case 'x':
      return Utils.utf8chr(Utils.hexDec(value.substr(2, 2)));
    case 'u':
      return Utils.utf8chr(Utils.hexDec(value.substr(2, 4)));
    case 'U':
      return Utils.utf8chr(Utils.hexDec(value.substr(2, 8)));
    default:
      return '';
  }
}
```
- example usage
```shell
...
  return value.replace(/\'\'/g, '\'');
};

Unescaper.unescapeDoubleQuotedString = function(value) {
  if (this._unescapeCallback == null) {
    this._unescapeCallback = (function(_this) {
      return function(str) {
        return _this.unescapeCharacter(str);
      };
    })(this);
  }
  return this.PATTERN_ESCAPED_CHARACTER.replace(value, this._unescapeCallback);
};

Unescaper.unescapeCharacter = function(value) {
...
```

#### <a name="apidoc.element.yamljs.Unescaper.unescapeDoubleQuotedString"></a>[function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeDoubleQuotedString (value)](#apidoc.element.yamljs.Unescaper.unescapeDoubleQuotedString)
- description and source-code
```javascript
unescapeDoubleQuotedString = function (value) {
  if (this._unescapeCallback == null) {
    this._unescapeCallback = (function(_this) {
      return function(str) {
        return _this.unescapeCharacter(str);
      };
    })(this);
  }
  return this.PATTERN_ESCAPED_CHARACTER.replace(value, this._unescapeCallback);
}
```
- example usage
```shell
...
  var i, match, output;
  i = context.i;
  if (!(match = this.PATTERN_QUOTED_SCALAR.exec(scalar.slice(i)))) {
    throw new ParseMore('Malformed inline YAML string (' + scalar.slice(i) + ').');
  }
  output = match[0].substr(1, match[0].length - 2);
  if ('"' === scalar.charAt(i)) {
    output = Unescaper.unescapeDoubleQuotedString(output);
  } else {
    output = Unescaper.unescapeSingleQuotedString(output);
  }
  i += match[0].length;
  context.i = i;
  return output;
};
...
```

#### <a name="apidoc.element.yamljs.Unescaper.unescapeSingleQuotedString"></a>[function <span class="apidocSignatureSpan">yamljs.Unescaper.</span>unescapeSingleQuotedString (value)](#apidoc.element.yamljs.Unescaper.unescapeSingleQuotedString)
- description and source-code
```javascript
unescapeSingleQuotedString = function (value) {
  return value.replace(/\'\'/g, '\'');
}
```
- example usage
```shell
...
  if (!(match = this.PATTERN_QUOTED_SCALAR.exec(scalar.slice(i)))) {
    throw new ParseMore('Malformed inline YAML string (' + scalar.slice(i) + ').');
  }
  output = match[0].substr(1, match[0].length - 2);
  if ('"' === scalar.charAt(i)) {
    output = Unescaper.unescapeDoubleQuotedString(output);
  } else {
    output = Unescaper.unescapeSingleQuotedString(output);
  }
  i += match[0].length;
  context.i = i;
  return output;
};

Inline.parseSequence = function(sequence, context) {
...
```



# <a name="apidoc.module.yamljs.Utils"></a>[module yamljs.Utils](#apidoc.module.yamljs.Utils)

#### <a name="apidoc.element.yamljs.Utils.Utils"></a>[function <span class="apidocSignatureSpan">yamljs.</span>Utils ()](#apidoc.element.yamljs.Utils.Utils)
- description and source-code
```javascript
function Utils() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Utils.getStringFromFile"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>getStringFromFile (path, callback)](#apidoc.element.yamljs.Utils.getStringFromFile)
- description and source-code
```javascript
getStringFromFile = function (path, callback) {
  var data, fs, j, len1, name, ref, req, xhr;
  if (callback == null) {
    callback = null;
  }
  xhr = null;
  if (typeof window !== "undefined" && window !== null) {
    if (window.XMLHttpRequest) {
      xhr = new XMLHttpRequest();
    } else if (window.ActiveXObject) {
      ref = ["Msxml2.XMLHTTP.6.0", "Msxml2.XMLHTTP.3.0", "Msxml2.XMLHTTP", "Microsoft.XMLHTTP"];
      for (j = 0, len1 = ref.length; j < len1; j++) {
        name = ref[j];
        try {
          xhr = new ActiveXObject(name);
        } catch (error) {}
      }
    }
  }
  if (xhr != null) {
    if (callback != null) {
      xhr.onreadystatechange = function() {
        if (xhr.readyState === 4) {
          if (xhr.status === 200 || xhr.status === 0) {
            return callback(xhr.responseText);
          } else {
            return callback(null);
          }
        }
      };
      xhr.open('GET', path, true);
      return xhr.send(null);
    } else {
      xhr.open('GET', path, false);
      xhr.send(null);
      if (xhr.status === 200 || xhr.status === 0) {
        return xhr.responseText;
      }
      return null;
    }
  } else {
    req = require;
    fs = req('fs');
    if (callback != null) {
      return fs.readFile(path, function(err, data) {
        if (err) {
          return callback(null);
        } else {
          return callback(String(data));
        }
      });
    } else {
      data = fs.readFileSync(path);
      if (data != null) {
        return String(data);
      }
      return null;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.yamljs.Utils.hexDec"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>hexDec (input)](#apidoc.element.yamljs.Utils.hexDec)
- description and source-code
```javascript
hexDec = function (input) {
  this.REGEX_HEXADECIMAL.lastIndex = 0;
  input = this.trim(input);
  if ((input + '').slice(0, 2) === '0x') {
    input = (input + '').slice(2);
  }
  return parseInt((input + '').replace(this.REGEX_HEXADECIMAL, ''), 16);
}
```
- example usage
```shell
...
        throw new ParseException('Custom object support when parsing a YAML file has been disabled.');
      }
      return null;
  }
  break;
case '0':
  if ('0x' === scalar.slice(0, 2)) {
    return Utils.hexDec(scalar);
  } else if (Utils.isDigits(scalar)) {
    return Utils.octDec(scalar);
  } else if (Utils.isNumeric(scalar)) {
    return parseFloat(scalar);
  } else {
    return scalar;
  }
...
```

#### <a name="apidoc.element.yamljs.Utils.isDigits"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>isDigits (input)](#apidoc.element.yamljs.Utils.isDigits)
- description and source-code
```javascript
isDigits = function (input) {
  this.REGEX_DIGITS.lastIndex = 0;
  return this.REGEX_DIGITS.test(input);
}
```
- example usage
```shell
...
    }
  }
  return this.dumpObject(value);
}
if (type === 'boolean') {
  return (value ? 'true' : 'false');
}
if (Utils.isDigits(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseInt(value)));
}
if (Utils.isNumeric(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseFloat(value)));
}
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
...
```

#### <a name="apidoc.element.yamljs.Utils.isEmpty"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>isEmpty (value)](#apidoc.element.yamljs.Utils.isEmpty)
- description and source-code
```javascript
isEmpty = function (value) {
  return !value || value === '' || value === '0' || (value instanceof Array && value.length === 0) || this.isEmptyObject(value);
}
```
- example usage
```shell
...
  exceptionOnInvalidType = false;
}
if (objectEncoder == null) {
  objectEncoder = null;
}
output = '';
prefix = (indent ? Utils.strRepeat(' ', indent) : '');
if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
  output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
} else {
  if (input instanceof Array) {
    for (i = 0, len = input.length; i < len; i++) {
      value = input[i];
      willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
      output += prefix + '-' + (willBeInlined ? ' ' : "\n") + this.dump(value, inline - 1, (willBeInlined ? 0 : indent + this.indentation
), exceptionOnInvalidType, objectEncoder) + (willBeInlined ? "\n" : '');
...
```

#### <a name="apidoc.element.yamljs.Utils.isEmptyObject"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>isEmptyObject (value)](#apidoc.element.yamljs.Utils.isEmptyObject)
- description and source-code
```javascript
isEmptyObject = function (value) {
  var k;
  return value instanceof Object && ((function() {
    var results;
    results = [];
    for (k in value) {
      if (!hasProp.call(value, k)) continue;
      results.push(k);
    }
    return results;
  })()).length === 0;
}
```
- example usage
```shell
...
    this.REGEX_RIGHT_TRIM_BY_CHAR[_char] = regexRight = new RegExp(_char + '' + _char + '*$');
  }
  regexRight.lastIndex = 0;
  return str.replace(regexRight, '');
};

Utils.isEmpty = function(value) {
  return !value || value === '' || value === '0' || (value instanceof Array && value.length === 0) || this.isEmptyObject(value);
};

Utils.isEmptyObject = function(value) {
  var k;
  return value instanceof Object && ((function() {
    var results;
    results = [];
...
```

#### <a name="apidoc.element.yamljs.Utils.isNumeric"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>isNumeric (input)](#apidoc.element.yamljs.Utils.isNumeric)
- description and source-code
```javascript
isNumeric = function (input) {
  this.REGEX_SPACES.lastIndex = 0;
  return typeof input === 'number' || typeof input === 'string' && !isNaN(input) && input.replace(this.REGEX_SPACES, '') !== '';
}
```
- example usage
```shell
...
}
if (type === 'boolean') {
  return (value ? 'true' : 'false');
}
if (Utils.isDigits(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseInt(value)));
}
if (Utils.isNumeric(value)) {
  return (type === 'string' ? "'" + value + "'" : String(parseFloat(value)));
}
if (type === 'number') {
  return (value === 2e308 ? '.Inf' : (value === -2e308 ? '-.Inf' : (isNaN(value) ? '.NaN' : value)));
}
if (Escaper.requiresDoubleQuoting(value)) {
  return Escaper.escapeWithDoubleQuotes(value);
...
```

#### <a name="apidoc.element.yamljs.Utils.ltrim"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>ltrim (str, _char)](#apidoc.element.yamljs.Utils.ltrim)
- description and source-code
```javascript
ltrim = function (str, _char) {
  var regexLeft;
  if (_char == null) {
    _char = '\\s';
  }
  regexLeft = this.REGEX_LEFT_TRIM_BY_CHAR[_char];
  if (regexLeft == null) {
    this.REGEX_LEFT_TRIM_BY_CHAR[_char] = regexLeft = new RegExp('^' + _char + '' + _char + '*');
  }
  regexLeft.lastIndex = 0;
  return str.replace(regexLeft, '');
}
```
- example usage
```shell
...
  };
}
i = context.i;
if (ref = scalar.charAt(i), indexOf.call(stringDelimiters, ref) >= 0) {
  output = this.parseQuotedScalar(scalar, context);
  i = context.i;
  if (delimiters != null) {
    tmp = Utils.ltrim(scalar.slice(i), ' ');
    if (!(ref1 = tmp.charAt(0), indexOf.call(delimiters, ref1) >= 0)) {
      throw new ParseException('Unexpected characters (' + scalar.slice(i) + ').');
    }
  }
} else {
  if (!delimiters) {
    output = scalar.slice(i);
...
```

#### <a name="apidoc.element.yamljs.Utils.octDec"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>octDec (input)](#apidoc.element.yamljs.Utils.octDec)
- description and source-code
```javascript
octDec = function (input) {
  this.REGEX_OCTAL.lastIndex = 0;
  return parseInt((input + '').replace(this.REGEX_OCTAL, ''), 8);
}
```
- example usage
```shell
...
      return null;
  }
  break;
case '0':
  if ('0x' === scalar.slice(0, 2)) {
    return Utils.hexDec(scalar);
  } else if (Utils.isDigits(scalar)) {
    return Utils.octDec(scalar);
  } else if (Utils.isNumeric(scalar)) {
    return parseFloat(scalar);
  } else {
    return scalar;
  }
  break;
case '+':
...
```

#### <a name="apidoc.element.yamljs.Utils.parseBoolean"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>parseBoolean (input, strict)](#apidoc.element.yamljs.Utils.parseBoolean)
- description and source-code
```javascript
parseBoolean = function (input, strict) {
  var lowerInput;
  if (strict == null) {
    strict = true;
  }
  if (typeof input === 'string') {
    lowerInput = input.toLowerCase();
    if (!strict) {
      if (lowerInput === 'no') {
        return false;
      }
    }
    if (lowerInput === '0') {
      return false;
    }
    if (lowerInput === 'false') {
      return false;
    }
    if (lowerInput === '') {
      return false;
    }
    return true;
  }
  return !!input;
}
```
- example usage
```shell
...
case '!str':
  return Utils.ltrim(scalar.slice(4));
case '!!str':
  return Utils.ltrim(scalar.slice(5));
case '!!int':
  return parseInt(this.parseScalar(scalar.slice(5)));
case '!!bool':
  return Utils.parseBoolean(this.parseScalar(scalar.slice(6)), false);
case '!!float':
  return parseFloat(this.parseScalar(scalar.slice(7)));
case '!!timestamp':
  return Utils.stringToDate(Utils.ltrim(scalar.slice(11)));
default:
  if (context == null) {
    context = {
...
```

#### <a name="apidoc.element.yamljs.Utils.rtrim"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>rtrim (str, _char)](#apidoc.element.yamljs.Utils.rtrim)
- description and source-code
```javascript
rtrim = function (str, _char) {
  var regexRight;
  if (_char == null) {
    _char = '\\s';
  }
  regexRight = this.REGEX_RIGHT_TRIM_BY_CHAR[_char];
  if (regexRight == null) {
    this.REGEX_RIGHT_TRIM_BY_CHAR[_char] = regexRight = new RegExp(_char + '' + _char + '*$');
  }
  regexRight.lastIndex = 0;
  return str.replace(regexRight, '');
}
```
- example usage
```shell
...
  }
} else {
  if (!delimiters) {
    output = scalar.slice(i);
    i += output.length;
    strpos = output.indexOf(' #');
    if (strpos !== -1) {
      output = Utils.rtrim(output.slice(0, strpos));
    }
  } else {
    joinedDelimiters = delimiters.join('|');
    pattern = this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters];
    if (pattern == null) {
      pattern = new Pattern('^(.+?)(' + joinedDelimiters + ')');
      this.PATTERN_SCALAR_BY_DELIMITERS[joinedDelimiters] = pattern;
...
```

#### <a name="apidoc.element.yamljs.Utils.strRepeat"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>strRepeat (str, number)](#apidoc.element.yamljs.Utils.strRepeat)
- description and source-code
```javascript
strRepeat = function (str, number) {
  var i, res;
  res = '';
  i = 0;
  while (i < number) {
    res += str;
    i++;
  }
  return res;
}
```
- example usage
```shell
...
if (exceptionOnInvalidType == null) {
  exceptionOnInvalidType = false;
}
if (objectEncoder == null) {
  objectEncoder = null;
}
output = '';
prefix = (indent ? Utils.strRepeat(' ', indent) : '');
if (inline <= 0 || typeof input !== 'object' || input instanceof Date || Utils.isEmpty(input)) {
  output += prefix + Inline.dump(input, exceptionOnInvalidType, objectEncoder);
} else {
  if (input instanceof Array) {
    for (i = 0, len = input.length; i < len; i++) {
      value = input[i];
      willBeInlined = inline - 1 <= 0 || typeof value !== 'object' || Utils.isEmpty(value);
...
```

#### <a name="apidoc.element.yamljs.Utils.stringToDate"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>stringToDate (str)](#apidoc.element.yamljs.Utils.stringToDate)
- description and source-code
```javascript
stringToDate = function (str) {
  var date, day, fraction, hour, info, minute, month, second, tz_hour, tz_minute, tz_offset, year;
  if (!(str != null ? str.length : void 0)) {
    return null;
  }
  info = this.PATTERN_DATE.exec(str);
  if (!info) {
    return null;
  }
  year = parseInt(info.year, 10);
  month = parseInt(info.month, 10) - 1;
  day = parseInt(info.day, 10);
  if (info.hour == null) {
    date = new Date(Date.UTC(year, month, day));
    return date;
  }
  hour = parseInt(info.hour, 10);
  minute = parseInt(info.minute, 10);
  second = parseInt(info.second, 10);
  if (info.fraction != null) {
    fraction = info.fraction.slice(0, 3);
    while (fraction.length < 3) {
      fraction += '0';
    }
    fraction = parseInt(fraction, 10);
  } else {
    fraction = 0;
  }
  if (info.tz != null) {
    tz_hour = parseInt(info.tz_hour, 10);
    if (info.tz_minute != null) {
      tz_minute = parseInt(info.tz_minute, 10);
    } else {
      tz_minute = 0;
    }
    tz_offset = (tz_hour * 60 + tz_minute) * 60000;
    if ('-' === info.tz_sign) {
      tz_offset *= -1;
    }
  }
  date = new Date(Date.UTC(year, month, day, hour, minute, second, fraction));
  if (tz_offset) {
    date.setTime(date.getTime() - tz_offset);
  }
  return date;
}
```
- example usage
```shell
...
case '!!int':
  return parseInt(this.parseScalar(scalar.slice(5)));
case '!!bool':
  return Utils.parseBoolean(this.parseScalar(scalar.slice(6)), false);
case '!!float':
  return parseFloat(this.parseScalar(scalar.slice(7)));
case '!!timestamp':
  return Utils.stringToDate(Utils.ltrim(scalar.slice(11)));
default:
  if (context == null) {
    context = {
      exceptionOnInvalidType: this.settings.exceptionOnInvalidType,
      objectDecoder: this.settings.objectDecoder,
      i: 0
    };
...
```

#### <a name="apidoc.element.yamljs.Utils.subStrCount"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>subStrCount (string, subString, start, length)](#apidoc.element.yamljs.Utils.subStrCount)
- description and source-code
```javascript
subStrCount = function (string, subString, start, length) {
  var c, i, j, len, ref, sublen;
  c = 0;
  string = '' + string;
  subString = '' + subString;
  if (start != null) {
    string = string.slice(start);
  }
  if (length != null) {
    string = string.slice(0, length);
  }
  len = string.length;
  sublen = subString.length;
  for (i = j = 0, ref = len; 0 <= ref ? j < ref : j > ref; i = 0 <= ref ? ++j : --j) {
    if (subString === string.slice(i, sublen)) {
      c++;
      i += sublen - 1;
    }
  }
  return c;
}
```
- example usage
```shell
...
  value = value.split("\r\n").join("\n").split("\r").join("\n");
}
count = 0;
ref = this.PATTERN_YAML_HEADER.replaceAll(value, ''), value = ref[0], count = ref[1];
this.offset += count;
ref1 = this.PATTERN_LEADING_COMMENTS.replaceAll(value, '', 1), trimmedValue = ref1[0], count = ref1[1];
if (count === 1) {
  this.offset += Utils.subStrCount(value, "\n") - Utils.subStrCount(trimmedValue, "\n");
  value = trimmedValue;
}
ref2 = this.PATTERN_DOCUMENT_MARKER_START.replaceAll(value, '', 1), trimmedValue = ref2[0], count = ref2[1];
if (count === 1) {
  this.offset += Utils.subStrCount(value, "\n") - Utils.subStrCount(trimmedValue, "\n");
  value = trimmedValue;
  value = this.PATTERN_DOCUMENT_MARKER_END.replace(value, '');
...
```

#### <a name="apidoc.element.yamljs.Utils.trim"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>trim (str, _char)](#apidoc.element.yamljs.Utils.trim)
- description and source-code
```javascript
trim = function (str, _char) {
  var regexLeft, regexRight;
  if (_char == null) {
    _char = '\\s';
  }
  return str.trim();
  regexLeft = this.REGEX_LEFT_TRIM_BY_CHAR[_char];
  if (regexLeft == null) {
    this.REGEX_LEFT_TRIM_BY_CHAR[_char] = regexLeft = new RegExp('^' + _char + '' + _char + '*');
  }
  regexLeft.lastIndex = 0;
  regexRight = this.REGEX_RIGHT_TRIM_BY_CHAR[_char];
  if (regexRight == null) {
    this.REGEX_RIGHT_TRIM_BY_CHAR[_char] = regexRight = new RegExp(_char + '' + _char + '*$');
  }
  regexRight.lastIndex = 0;
  return str.replace(regexLeft, '').replace(regexRight, '');
}
```
- example usage
```shell
...
  objectDecoder = null;
}
this.settings.exceptionOnInvalidType = exceptionOnInvalidType;
this.settings.objectDecoder = objectDecoder;
if (value == null) {
  return '';
}
value = Utils.trim(value);
if (0 === value.length) {
  return '';
}
context = {
  exceptionOnInvalidType: exceptionOnInvalidType,
  objectDecoder: objectDecoder,
  i: 0
...
```

#### <a name="apidoc.element.yamljs.Utils.utf8chr"></a>[function <span class="apidocSignatureSpan">yamljs.Utils.</span>utf8chr (c)](#apidoc.element.yamljs.Utils.utf8chr)
- description and source-code
```javascript
utf8chr = function (c) {
  var ch;
  ch = String.fromCharCode;
  if (0x80 > (c %= 0x200000)) {
    return ch(c);
  }
  if (0x800 > c) {
    return ch(0xC0 | c >> 6) + ch(0x80 | c & 0x3F);
  }
  if (0x10000 > c) {
    return ch(0xE0 | c >> 12) + ch(0x80 | c >> 6 & 0x3F) + ch(0x80 | c & 0x3F);
  }
  return ch(0xF0 | c >> 18) + ch(0x80 | c >> 12 & 0x3F) + ch(0x80 | c >> 6 & 0x3F) + ch(0x80 | c & 0x3F);
}
```
- example usage
```shell
...
  case '_':
    return ch(0x00A0);
  case 'L':
    return ch(0x2028);
  case 'P':
    return ch(0x2029);
  case 'x':
    return Utils.utf8chr(Utils.hexDec(value.substr(2, 2)));
  case 'u':
    return Utils.utf8chr(Utils.hexDec(value.substr(2, 4)));
  case 'U':
    return Utils.utf8chr(Utils.hexDec(value.substr(2, 8)));
  default:
    return '';
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
