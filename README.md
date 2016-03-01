# babel-preset-es2015-without-strict-and-regenerator

> `babel-preset-es2015` - (`babel-plugin-transform-strict-mode` + `babel-plugin-transform-regenerator`)

## Install

```sh
$ npm install --save-dev babel-preset-es2015-without-strict-and-regenerator
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-without-strict-and-regenerator"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-without-strict-and-regenerator
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-without-strict-and-regenerator"]
});
```
