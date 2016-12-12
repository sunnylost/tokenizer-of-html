# tokenize-html

[![npm](https://img.shields.io/npm/v/tokenizer-of-html.svg)](https://www.npmjs.com/package/tokenizer-of-html)

A HTML tokenizer

## How to use

```javascript
var HTMLTokenizer = require( 'tokenizer-of-html' )

var tokens = HTMLTokenizer.tokenize( '<div></div>' )

//look up token type
HTMLTokenizer.type.startTag === tokens[ 0 ].type
```
