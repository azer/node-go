## just-next-tick (or go)

Cross-platform next-tick with fallback to setTimeout.

## Install

```bash
$ npm install just-next-tick
```

It's also available as `go`:

```bash
$ npm install go
```

## Usage

```js
nextTick = require('just-next-tick')

nextTick(function () {
  console.log('world')
})

console.log('hello')

// hello
// world
```
