# tokenize-html

[![Build Status](https://travis-ci.org/GitbookIO/tokenize-html.png?branch=master)](https://travis-ci.org/GitbookIO/tokenize-html)
[![NPM version](https://badge.fury.io/js/tokenize-html.svg)](http://badge.fury.io/js/tokenize-html)

Tokenize an html string into a list of text tokens, it keeps reference to index in the original string.

### Installation

```
$ npm install tokenize-text
```

### Usage

```js
var tokenizeHTML = require('tokenize-html');


var tokens = tokenizeHTML('<b>hello</b> world');

/*
[ { value: 'hello', index: 3, offset: 5 },
  { value: ' world', index: 12, offset: 6 } ]
*/
```
