# Force Require

![Last version](https://img.shields.io/github/tag/Kikobeats/parse-json.svg?style=flat-square)
[![Build Status](http://img.shields.io/travis/Kikobeats/force-require/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/force-require)
[![Dependency status](http://img.shields.io/david/Kikobeats/force-require.svg?style=flat-square)](https://david-dm.org/Kikobeats/force-require)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/force-require.svg?style=flat-square)](https://david-dm.org/Kikobeats/force-require#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/force-require.svg?style=flat-square)](https://www.npmjs.org/package/force-require)
[![Gittip](http://img.shields.io/gittip/Kikobeats.svg?style=flat-square)](https://www.gittip.com/Kikobeats/)

> Ensure that a NPM dependency is resolved.

## Install

```bash
npm install force-require --save
```

## Usage

First load the library:

```js
var forceRequire = require('force-require');
```
Now you can use like `require` command.

## API

### force-require(&lt;String&gt;)

Try to load a dependency based in the name. Internally the library:

- Try to resolve the dependency locally.
- Later try to resolve the dependency globally.
- If not possible to resolve locally or globally, then the dependency will be installed globally and it's required.

## License

MIT © [Kiko Beats](http://kikobeats.com)


