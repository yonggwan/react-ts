<!--
    Webpack configuration referrence.
    https://typescript-kr.github.io/pages/tutorials/react-&-webpack.html

    eslint + prettier configuration referrence.
    https://www.robertcooper.me/using-eslint-and-prettier-in-a-typescript-project
 -->

[![node][node]][node-url] [![npm][npm]][npm-url] [![typescript][typescript]][typescript-url] [![react][react]][react-url]

# A simple boilerplate for frontend

- Self configuration A-Z

## Main stack

<ol>
  <li>react.js</li>
  <li>typescript</li>
  <li>css-in-js (jss)</li>
  <li>material-ui</li>
</ol>

## run project

```sh
npm install & npm run dev
```

then open `http://localhost:3000/`

## build

```sh
npm run build:dev
npm run build:prod
```

## What's includeds?

- webpack dev server with [HMR][hmr-url]
- eslint + prettier (auto formatting)
- vscode setting file (theme, etc configs)
- build optimization (next job)
  chunk/tree-shake/minify

### VScode custom setting

[.vscode/settings.json](./docs/vscode_settings.json.md)
VSCode Theme: `One Dark Pro`

### My VScode extensions

![My VScode extensions](docs/extensions_capture.png)

[node]: https://img.shields.io/badge/node-^12.18.3-green
[node-url]: https://nodejs.org/en/
[npm]: https://img.shields.io/badge/npm-^6.14.6-red
[npm-url]: https://npmjs.com/package/npm
[typescript]: https://img.shields.io/badge/typescript-^4.0.2-blue
[typescript-url]: https://www.npmjs.com/package/typescript
[react]: https://img.shields.io/badge/react-^16.13.1-blue
[react-url]: https://www.npmjs.com/package/react
[hmr-url]: https://webpack.js.org/concepts/hot-module-replacement
