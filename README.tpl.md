# BchAddr.js: Bitcoin Cash general purpose address translation for Node.js and web browsers.

[![Build Status](https://travis-ci.org/bitcoincashjs/bchaddrjs.svg?branch=master)](https://travis-ci.org/bitcoincashjs/bchaddrjs) [![Coverage Status](https://coveralls.io/repos/github/bitcoincashjs/bchaddrjs/badge.svg?branch=master)](https://coveralls.io/github/bitcoincashjs/bchaddrjs?branch=master)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

[![NPM](https://nodei.co/npm/bchaddrjs.png?downloads=true)](https://nodei.co/npm/bchaddrjs/)

[![JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

Plug & Play JavaScript library for all Bitcoin Cash address format translation needs. Easy-to-use, thoroughly tested, and feature complete.

Support for the new Bitcoin Cash address [format](https://github.com/Bitcoin-UAHF/spec/blob/master/bchaddr.md) which improves upon [BIP 173](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki), as well as the Bitpay and Legacy formats.

Test out a demo address translator powered by BchAddr.js [here](https://bitcoincashjs.github.io/address/).

## Installation

### Using NPM

```bsh
$ npm install --save bchaddrjs
```

### Using Bower

```bsh
$ bower install --save bchaddrjs
```

### Manually

You may also download the distribution file manually and place it within your third-party scripts directory: [dist/bchaddrjs-{{ version }}.min.js](https://cdn.rawgit.com/bitcoincashjs/bchaddrjs/master/dist/bchaddrjs-{{ version }}.min.js).

## Usage

### In Node.js

```javascript
var bchaddr = require('bchaddrjs');
```

### Browser

#### Script Tag

You may include a script tag in your HTML and the `bchaddr` module will be defined globally on subsequent scripts.

```html
<html>
  <head>
    ...
    <script src="https://cdn.rawgit.com/bitcoincashjs/bchaddrjs/master/dist/bchaddrjs-{{ version }}.min.js"></script>
  </head>
  ...
</html>
```

## Documentation

### Generate and Browse Locally

```bsh
$ npm run docs
```

### Online

Browse automatically generated jsdocs [online](https://cdn.rawgit.com/bitcoincashjs/bchaddrjs/master/docs/index.html).
