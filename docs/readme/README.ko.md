<h1 align="center">UI 레퍼런스 화면 모음</h1>

<p align="center">
  [English](../readme/README.en.md) | **한국어** | [简体中文](../readme/README.zh.md) | [日本語](../readme/README.ja.md) | [Español](../readme/README.es.md) | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | [العربية](../readme/README.ar.md) | [हिन्दी](../readme/README.hi.md) • [📜 변경 이력](../changelog/CHANGELOG.ko.md)
</p>

---

> 독립 실행 가능한 HTML 레퍼런스 화면 248개 — API 게이트웨이 운영 콘솔과 에디토리얼 랜딩 페이지.

### [▶ 라이브 갤러리](https://krcupro.github.io/ui-reference-screens/)

브라우저에서 전체 화면 둘러보기

## 어떤 모습인가

![어떤 모습인가](../assets/gallery-demo.gif)

*목록에 마우스를 올리면 실제 화면이 미리 보입니다. 제목·뷰포트로 걸러낼 수 있습니다.*

| 데스크톱 화면은 1280px로 렌더링 | 모바일 화면은 390px로 렌더링 |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## 특징

- **올리면 바로 미리보기.** 목록을 가리키면 그 자리에서 실제 화면이 렌더링됩니다. 썸네일 이미지도, 외부에서 받아오는 것도 없습니다.
- **각자의 뷰포트 크기로.** 모바일은 390px, 데스크톱은 1280px로 미리 보여서 뭉치거나 흐려지지 않습니다.
- **파일 하나로 완결.** 화면마다 HTML 한 개이고, 빌드 없이 브라우저에서 바로 열립니다.
- **입력하는 대로 걸러짐.** 제목 검색, 뷰포트 필터, 영역 이동을 지원합니다. `/` 키로 검색창에 바로 갑니다.
- **밝은 테마와 어두운 테마.** 갤러리가 시스템 설정을 따라갑니다.

## 구성

| 영역 | 화면 수 |
| --- | ---: |
| Marginalia — 랜딩 페이지 | 94 |
| 콘솔 — 개요 | 25 |
| 콘솔 — 키 | 18 |
| 콘솔 — 분석 | 17 |
| 콘솔 — 스크린 | 12 |
| 콘솔 — 디자인 시스템 | 21 |
| 콘솔 — 로그 | 7 |
| 콘솔 — 설정 | 13 |
| 콘솔 — MCP | 6 |
| 콘솔 — 플레이그라운드 | 2 |
| 콘솔 — 기타 | 33 |
| **합계** | **248** |

## 뷰포트

| 뷰포트 | 화면 수 | 렌더링 폭 |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## 디렉터리 구조

```
index.html                 gallery
catalog.json               metadata for all 248 screens
screens/
  marginalia-landing/      94
  operations-console/      154
docs/
  readme/                  9 languages
  changelog/               9 languages
  assets/
```

## 사용법

1. [라이브 갤러리](https://krcupro.github.io/ui-reference-screens/)를 열면 됩니다. 설치할 것이 없습니다.
2. 또는 클론해서 `index.html`을 직접 열어도 됩니다:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

화면 하나당 항목 하나:

```json
{
  "file": "screens/operations-console/overview/dashboard-overview.html",
  "title": "Dashboard Overview",
  "category": "operations-console/overview",
  "device": "DESKTOP",
  "prompt": "⚡ 외부 MCP 에이전트 연동으로 생성됨",
  "createdAt": "2026-08-31T13:54:01.252Z"
}
```

## 참고

- 화면은 전부 정적 목업입니다. 표시된 값은 예시로 지어낸 것이며 실제 계정·키·호스트·개인정보는 어디에도 없습니다.
- 타이포그래피만 Google Fonts에서 네트워크로 불러오고, 나머지는 전부 인라인입니다.
- 같은 제목이 상태별로 반복됩니다 — 로딩, 빈 상태, 오류, 첫 실행, 성능 저하.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">라이브 갤러리</a> · <a href="../../README.md">메인 README로 돌아가기</a>
</p>
