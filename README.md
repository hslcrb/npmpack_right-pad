<p align="center">
  <a href="https://github.com/hslcrb/npmpack_right-pad">
    <img src="logo.png" width="400" alt="right-pad logo">
  </a>
</p>

# right-pad

> An ultra-lightweight, zero-dependency TypeScript package to append a single space to the right of a string.

[![npm version](https://img.shields.io/npm/v/right-pad.svg?style=flat-square)](https://www.npmjs.com/package/right-pad)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue.svg?style=flat-square)](https://www.typescriptlang.org/)

[한국어 문서 (Korean)](./README_ko.md)

---

## 🚀 Features

- **Ultra Lightweight**: Zero dependencies, minimal footprint.
- **TypeScript Optimized**: Full type safety with zero configuration.
- **High Performance**: Single-line optimized arrow function for maximum speed.
- **Clean API**: Simple and intuitive design.

## 📦 Installation

```bash
# Using npm
npm install right-pad

# Using yarn
yarn add right-pad

# Using pnpm
pnpm add right-pad
```

## 🛠 Usage

The goal of this package is to keep things as simple as possible.

### Basic Usage

```typescript
import pad from 'right-pad';

const text = 'hello';
const padded = pad(text);

console.log(`'${padded}'`); // 'hello '
console.log(padded.length); // 6
```

### In Plain JavaScript

```javascript
const pad = require('right-pad');

console.log(pad('world')); // 'world '
```

## 📄 Documentation

- [Contributing Guide](./CONTRIBUTING.md)
- [Changelog](./CHANGELOG.md)
- [MIT License](./LICENSE)

---

## 👤 Author

**Rheehose (Rhee Creative)**
- GitHub: [@hslcrb](https://github.com/hslcrb)

---

Copyright © 2008-2026 [Rheehose (Rhee Creative)](https://github.com/hslcrb).<br />
This project is [MIT](https://opensource.org/licenses/MIT) licensed.
