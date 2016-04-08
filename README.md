peer-info JavaScript implementation
===================================

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![Build Status](https://travis-ci.org/diasdavid/js-peer-info.svg?style=flat-square)](https://travis-ci.org/diasdavid/js-peer-info)
[![Dependency Status](https://david-dm.org/diasdavid/js-peer-info.svg?style=flat-square)](https://david-dm.org/diasdavid/js-peer-info)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard)

> Peer Info contains information about a peer Id and its multiaddrs. This module is used by IPFS and libp2p.

# Installation

## npm

```sh
> npm i peer-info
```

## Use in Node.js

```JavaScript
var PeerInfo = require('peer-info')
```

## Use in a browser with browserify, webpack or any other bundler

The code published to npm that gets loaded on require is in fact a ES5 transpiled version with the right shims added. This means that you can require it and use with your favourite bundler without having to adjust asset management process.

```JavaScript
var PeerInfo = require('peer-info')
```

## Use in a browser Using a script tag

Loading this module through a script tag will make the `PeerInfo` obj available in the global namespace.

```html
<script src="https://npmcdn.com/peer-info/dist/index.min.js"></script>
<!-- OR -->
<script src="https://npmcdn.com/peer-info/dist/index.js"></script>
```

# Usage

**DOCS IN PROGRESS**
