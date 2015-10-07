# tokenize-htmltext

[![Build Status](https://travis-ci.org/GitbookIO/tokenize-htmltext.png?branch=master)](https://travis-ci.org/GitbookIO/tokenize-htmltext)
[![NPM version](https://badge.fury.io/js/tokenize-htmltext.svg)](http://badge.fury.io/js/tokenize-htmltext)

Tokenize an html string into a list of text tokens, it keeps reference to indexes in the original string.

### Installation

```
$ npm install tokenize-text
```

### Usage

```js
var tokenizeHTML = require('tokenize-htmltext');


var tokens = tokenizeHTML('<b>hello</b> world');

/*
[ { value: 'hello', index: 3, offset: 5 },
  { value: ' world', index: 12, offset: 6 } ]
*/
```
