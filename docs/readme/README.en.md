<h1 align="center">UI Reference Screens</h1>

<p align="center">
  **English** | [한국어](../readme/README.ko.md) | [简体中文](../readme/README.zh.md) | [日本語](../readme/README.ja.md) | [Español](../readme/README.es.md) | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | [العربية](../readme/README.ar.md) | [हिन्दी](../readme/README.hi.md) • [📜 Changelog](../changelog/CHANGELOG.md)
</p>

---

> 248 standalone HTML reference screens — an API gateway operations console and an editorial landing page.

### [▶ Live gallery](https://krcupro.github.io/ui-reference-screens/)

Browse all screens in the browser

## What it looks like

![What it looks like](../assets/gallery-demo.gif)

*Hover any row to preview the real screen; filter by title or viewport.*

| Desktop screens render at 1280px | Mobile screens render at 390px |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## Highlights

- **Hover to preview.** Pointing at a row renders the actual screen in place — no thumbnail images, nothing fetched from anywhere else.
- **Sized to its own viewport.** A mobile layout previews at 390px and a desktop one at 1280px, so neither collapses nor blurs.
- **Self-contained files.** Every screen is one HTML file that opens in a browser with no build step and no local dependencies.
- **Filter as you type.** Search by title, narrow by viewport, jump between areas; press `/` to focus the search box.
- **Light and dark.** The gallery follows the system theme.

## Contents

| Area | Screens |
| --- | ---: |
| Marginalia — landing page | 94 |
| Console — overview | 25 |
| Console — keys | 18 |
| Console — analytics | 17 |
| Console — screens | 12 |
| Console — design system | 21 |
| Console — logs | 7 |
| Console — settings | 13 |
| Console — MCP | 6 |
| Console — playground | 2 |
| Console — other | 33 |
| **Total** | **248** |

## Viewports

| Viewport | Screens | Rendered width |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## Layout

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

## Using this repository

1. Open the [live gallery](https://krcupro.github.io/ui-reference-screens/) — nothing to install.
2. Or clone it and open `index.html` directly:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

One entry per screen:

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

## Notes

- Screens are static mockups. Every value shown in them is invented for illustration — no real accounts, keys, hosts or personal data appear anywhere.
- Typography loads from Google Fonts over the network; everything else is inline.
- Some titles repeat across different states — loading, empty, error, first-run, degraded.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">Live gallery</a> · <a href="../../README.md">Back to the main README</a>
</p>
