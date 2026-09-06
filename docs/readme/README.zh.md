<h1 align="center">UI 参考屏幕集</h1>

<p align="center">
  [English](../readme/README.en.md) | [한국어](../readme/README.ko.md) | **简体中文** | [日本語](../readme/README.ja.md) | [Español](../readme/README.es.md) | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | [العربية](../readme/README.ar.md) | [हिन्दी](../readme/README.hi.md) • [📜 更新日志](../changelog/CHANGELOG.zh.md)
</p>

---

> 248 个独立的 HTML 参考屏幕 —— 一个 API 网关运营控制台和一个编辑风格落地页。

### [▶ 在线画廊](https://krcupro.github.io/ui-reference-screens/)

在浏览器中浏览全部屏幕

## 实际效果

![实际效果](../assets/gallery-demo.gif)

*把鼠标移到任意一行即可预览真实屏幕；可按标题或视口筛选。*

| 桌面屏幕以 1280px 渲染 | 移动屏幕以 390px 渲染 |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## 亮点

- **悬停即预览。** 指向某一行就会就地渲染真实屏幕——没有缩略图，也不从别处拉取任何东西。
- **按各自的视口尺寸显示。** 移动端以 390px、桌面端以 1280px 预览，既不会挤成一团也不会发虚。
- **单文件自包含。** 每个屏幕都是一个 HTML 文件，无需构建即可在浏览器中打开。
- **边输入边筛选。** 支持标题搜索、视口筛选与区域跳转；按 `/` 直接聚焦搜索框。
- **亮色与暗色。** 画廊跟随系统主题。

## 内容

| 区域 | 屏幕数 |
| --- | ---: |
| Marginalia — 落地页 | 94 |
| 控制台 — 概览 | 25 |
| 控制台 — 密钥 | 18 |
| 控制台 — 分析 | 17 |
| 控制台 — 屏幕 | 12 |
| 控制台 — 设计系统 | 21 |
| 控制台 — 日志 | 7 |
| 控制台 — 设置 | 13 |
| 控制台 — MCP | 6 |
| 控制台 — 调试台 | 2 |
| 控制台 — 其他 | 33 |
| **合计** | **248** |

## 视口

| 视口 | 屏幕数 | 渲染宽度 |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## 目录结构

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

## 如何使用

1. 打开[在线画廊](https://krcupro.github.io/ui-reference-screens/)，无需安装任何东西。
2. 或者克隆仓库并直接打开 `index.html`：

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

每个屏幕对应一条记录：

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

## 说明

- 这些屏幕都是静态样稿。其中显示的数值均为示例虚构，不含任何真实账号、密钥、主机或个人数据。
- 仅字体通过网络加载自 Google Fonts，其余内容全部内联。
- 部分标题会以不同状态重复出现——加载中、空状态、错误、首次运行、降级。

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">在线画廊</a> · <a href="../../README.md">返回主 README</a>
</p>
