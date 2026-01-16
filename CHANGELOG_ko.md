<img src="logo.png" width="120" align="right" alt="right-pad logo">

# 변경 사항 (Changelog)

이 프로젝트의 모든 주요 변경 사항은 이 파일에 기록됩니다. 이 프로젝트는 [유의적 버전(Semantic Versioning)](https://semver.org/spec/v2.0.0.html) 형식을 준수합니다.

[English Changelog (영어)](./CHANGELOG.md)

---

## [1.0.0] - 2026-01-16

`right-pad`의 최초 정식 릴리스입니다.

### ✨ 추가됨
- **핵심 기능**: 문자열 뒤에 공백 하나를 추가하는 `rightPad` 함수 및 기본 내보내기 기능 도입.
- **타입스크립트**: `.d.ts` 타입 정의 파일을 포함한 완벽한 TypeScript 지원.
- **브랜딩**: 공식 "right-pad" 프리미엄 로고 디자인 적용.
- **문서화**: 다음을 포함한 상세한 한영 병기 문서 제공:
  - `README.md` & `README_ko.md`
  - `CONTRIBUTING.md` & `CONTRIBUTING_ko.md`
  - `CHANGELOG.md` & `CHANGELOG_ko.md`
- **테스트**: `ts-node`를 활용한 기능 검증 테스트 스위트 구축.
- **배포 설정**: npm 배포를 위한 `package.json` 최적화.

### ⚡ 성능 및 최적화
- O(1) 시간 복잡도를 갖는 문자열 결합 방식의 최소화된 구현.
- 배포 패키지 내 불필요한 파일을 제거하여 파일 크기를 최소화.

---

*향후 업데이트 버전은 [GitHub 프로젝트](https://github.com/hslcrb/npmpack_right-pad)를 참고해 주세요.*
