# @gxmari007/vite-plugin-eslint

[![npm (scoped)](https://img.shields.io/npm/v/@gxmari007/vite-plugin-eslint)](https://www.npmjs.com/package/@gxmari007/vite-plugin-eslint)
[![GitHub license](https://img.shields.io/github/license/gxmari007/vite-plugin-eslint)](https://github.com/gxmari007/vite-plugin-eslint/blob/master/LICENSE)

A vite ESLint plugin.

## Install

```
npm install @gxmari007/vite-plugin-eslint --save-dev
# or
yarn add @gxmari007/vite-plugin-eslint --dev
```

## Usage

```js
import { defineConfig } from 'vite';
import eslintPlugin from '@gxmari007/vite-plugin-eslint';

export default defineConfig({
  plugins: [eslintPlugin()],
});
```

## Options

### include

- **Type** `string | string[]`

  A single file, or array of files, to include when linting.

### exclude

- **Type** `string | string[]`

  A single file, or array of files, to exclude when linting.

### formatter

- **Type** `string | ESLint.Formatter`

  Custom error formatter or the name of a built-in formatter.

## License

MIT
