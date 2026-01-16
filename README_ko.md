<p align="center">
  <a href="https://github.com/hslcrb/npmpack_right-pad">
    <img src="logo.png" width="400" alt="right-pad logo">
  </a>
</p>

# right-pad

> 문자열 오른쪽에 공백 한 칸을 추가하는 초경량, 무의존성 타입스크립트 패키지입니다.

[![npm version](https://img.shields.io/npm/v/right-pad.svg?style=flat-square)](https://www.npmjs.com/package/right-pad)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue.svg?style=flat-square)](https://www.typescriptlang.org/)

[English (영어)](./README.md)

---

## 🚀 주요 특징

- **초경량**: 의존성이 전혀 없으며 용량이 매우 작습니다.
- **타입스크립트 최적화**: 설정 없이도 완벽한 타입 추론을 지원합니다.
- **고성능**: 최대 속도를 위해 최적화된 한 줄 화살표 함수 구성을 사용합니다.
- **명확한 API**: 직관적이고 쉬운 구성을 유지합니다.

## 📦 설치

```bash
# npm 사용 시
npm install right-pad

# yarn 사용 시
yarn add right-pad

# pnpm 사용 시
pnpm add right-pad
```

## 🛠 사용법

프로젝트의 목표는 가능한 한 단순하게 유지하는 것입니다.

### 기본 사용법

```typescript
import pad from 'right-pad';

const text = '안녕';
const padded = pad(text);

console.log(`'${padded}'`); // '안녕 '
console.log(padded.length); // 3 (공백 포함)
```

### 일반 자바스크립트에서 사용

```javascript
const pad = require('right-pad');

console.log(pad('반가워')); // '반가워 '
```

## 📄 문서 링크

- [기여 가이드](./CONTRIBUTING_ko.md)
- [변경 사항](./CHANGELOG_ko.md)
- [MIT 라이선스](./LICENSE)

---

## 👤 개발자

**Rheehose (Rhee Creative)**
- GitHub: [@hslcrb](https://github.com/hslcrb)

---

Copyright © 2008-2026 [Rheehose (Rhee Creative)](https://github.com/hslcrb).<br />
이 프로젝트는 [MIT](https://opensource.org/licenses/MIT) 라이선스를 따릅니다.
