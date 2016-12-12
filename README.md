# tokenize-html
A HTML tokenizer

## How to use

```javascript
var HTMLTokenizer = require( 'tokenize-html' )

var tokens = HTMLTokenizer.tokenize( '<div></div>' )

//look up token type
HTMLTokenizer.type.startTag === tokens[ 0 ].type
```
