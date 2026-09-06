# UI Reference Screens

A collection of 248 standalone HTML reference screens for two products: an API gateway
operations console and an editorial landing page. Each file is self-contained — open it in a
browser and it renders on its own, with no build step and no local dependencies.

## Contents

| Area | Screens |
| --- | ---: |
| `marginalia-landing` | 94 |
| `operations-console/overview` | 25 |
| `operations-console/keys` | 18 |
| `operations-console/analytics` | 17 |
| `operations-console/screens` | 12 |
| `operations-console/design` | 21 |
| `operations-console/logs` | 7 |
| `operations-console/settings` | 13 |
| `operations-console/mcp` | 6 |
| `operations-console/playground` | 2 |
| `operations-console/other` | 33 |
| **Total** | **248** |

## Viewports

| Device | Screens |
| --- | ---: |
| DESKTOP | 165 |
| MOBILE | 54 |
| TABLET | 29 |

## Layout

```
screens/
  marginalia-landing/
  operations-console/overview/
  operations-console/keys/
  operations-console/analytics/
  operations-console/screens/
  operations-console/design/
  operations-console/logs/
  operations-console/settings/
  operations-console/mcp/
  operations-console/playground/
  operations-console/other/
catalog.json      metadata for every screen (title, area, viewport, prompt, timestamp)
index.html        browsable gallery of all screens
```

## catalog.json

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

- Screens are static mockups. Data shown in them is invented for illustration —
  no real accounts, keys, hosts or personal data appear anywhere.
- Typography is pulled from Google Fonts over the network; everything else is inline.
- Screens were produced across several iterations, so some titles repeat with
  different states (loading, empty, error, first-run, degraded).
