<h1 align="center">UI リファレンス画面集</h1>

<p align="center">
  [English](../readme/README.en.md) | [한국어](../readme/README.ko.md) | [简体中文](../readme/README.zh.md) | **日本語** | [Español](../readme/README.es.md) | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | [العربية](../readme/README.ar.md) | [हिन्दी](../readme/README.hi.md) • [📜 変更履歴](../changelog/CHANGELOG.ja.md)
</p>

---

> 単体で動作する HTML リファレンス画面 248 点 — API ゲートウェイ運用コンソールとエディトリアル調のランディングページ。

### [▶ ライブギャラリー](https://krcupro.github.io/ui-reference-screens/)

ブラウザーで全画面を見る

## 見た目

![見た目](../assets/gallery-demo.gif)

*行にマウスを載せると実際の画面がプレビューされます。タイトルやビューポートで絞り込めます。*

| デスクトップ画面は 1280px で描画 | モバイル画面は 390px で描画 |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## 特徴

- **載せるだけでプレビュー。** 行を指すとその場で実際の画面が描画されます。サムネイル画像も、外部からの取得もありません。
- **それぞれのビューポート幅で表示。** モバイルは 390px、デスクトップは 1280px で描画するため、潰れることもぼやけることもありません。
- **1 ファイルで完結。** 各画面は HTML 1 枚で、ビルドなしにブラウザーで開けます。
- **入力しながら絞り込み。** タイトル検索、ビューポート絞り込み、エリア移動に対応。`/` キーで検索欄に移動します。
- **ライトとダーク。** ギャラリーはシステム設定に追従します。

## 内容

| エリア | 画面数 |
| --- | ---: |
| Marginalia — ランディングページ | 94 |
| コンソール — 概要 | 25 |
| コンソール — キー | 18 |
| コンソール — 分析 | 17 |
| コンソール — スクリーン | 12 |
| コンソール — デザインシステム | 21 |
| コンソール — ログ | 7 |
| コンソール — 設定 | 13 |
| コンソール — MCP | 6 |
| コンソール — プレイグラウンド | 2 |
| コンソール — その他 | 33 |
| **合計** | **248** |

## ビューポート

| ビューポート | 画面数 | 描画幅 |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## ディレクトリ構成

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

## 使い方

1. [ライブギャラリー](https://krcupro.github.io/ui-reference-screens/)を開くだけです。インストールは不要です。
2. あるいはクローンして `index.html` を直接開いてください:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

画面 1 件につき 1 エントリ:

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

## 補足

- 画面はすべて静的モックアップです。表示されている値は説明用に作られたもので、実在するアカウント・キー・ホスト・個人情報は含まれません。
- タイポグラフィのみ Google Fonts からネットワーク経由で読み込み、それ以外はすべてインラインです。
- 同じタイトルが状態違いで繰り返し登場します — 読み込み中、空、エラー、初回起動、劣化。

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">ライブギャラリー</a> · <a href="../../README.md">メイン README に戻る</a>
</p>
