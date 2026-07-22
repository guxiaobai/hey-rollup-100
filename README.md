# Rollup

> `rollup.config.js`


## 路线图

* format: `commonjs（cjs）`、`iife`、`amd`、`umd`
* `rollup.config.js`
* `commonjs()`、`nodeResolve()`
* `globals`、`external`
* `babel()`、`terser()`
* `postcss()`
* `vue`


```bash
pnpm add rollup -D
```

```bash
pnpx rollup ./src/783.js -o dist/bundle.js
```

```bash
pnpx rollup -c
```

## Vue

```bash
pnpm add vue
pnpm add rollup-plugin-vue @vue/compiler-sfc -D
```
```bash
pnpm add @rollup/plugin-replace -D
```

## Plugins

名字|备注
---|---
[@rollup/plugin-commonjs](https://github.com/rollup/plugins/tree/master/packages/commonjs) | commonjs
[@rollup/plugin-node-resolve](https://github.com/rollup/plugins/tree/master/packages/node-resolve)| node_modules 
[@rollup/plugin-babel](https://github.com/rollup/plugins/tree/master/packages/babel) | Babel
[@rollup/plugin-terser](https://github.com/rollup/plugins/tree/master/packages/terser) | Terser
[@rollup/plugin-html](https://github.com/rollup/plugins/tree/master/packages/html) | Html
[rollup-plugin-postcss](https://github.com/egoist/rollup-plugin-postcss) | PostCSS

## Ref



* <https://rollupjs.org/>
* <https://www.rollupjs.com/>