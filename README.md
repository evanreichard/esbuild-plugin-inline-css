# esbuild-plugin-inline-css

A esbuild plugin used to bundle and embed CSS into JS.

## Install

```shell
# NPM
npm i -D esbuild-plugin-inline-css

# YARN
yarn add -D esbuild-plugin-inline-css
```

## Usage

```js
const esbuild = require('esbuild');
const InlineCSSPlugin = require('esbuild-plugin-inline-css');

esbuild.build({
    plugins: [
        InlineCSSPlugin()
    ]
});
```
