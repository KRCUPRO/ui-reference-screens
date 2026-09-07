<h1 align="center">Écrans de référence UI</h1>

<p align="center">
  <a href="../readme/README.en.md">English</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.ko.md">한국어</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.zh.md">简体中文</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.ja.md">日本語</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.es.md">Español</a>
  &nbsp;|&nbsp;
  <b>Français</b>
  &nbsp;|&nbsp;
  <a href="../readme/README.ru.md">Русский</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.ar.md">العربية</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.hi.md">हिन्दी</a>
  &nbsp;•&nbsp;
  <a href="../changelog/CHANGELOG.fr.md">📜 Journal des modifications</a>
</p>

---

> 248 écrans de référence en HTML autonome : une console d'exploitation de passerelle d'API et une page d'accueil éditoriale.

### [▶ Galerie en ligne](https://krcupro.github.io/ui-reference-screens/)

Parcourir tous les écrans dans le navigateur

## Aperçu

![Aperçu](../assets/gallery-demo.gif)

*Survolez une ligne pour prévisualiser l'écran réel ; filtrez par titre ou par viewport.*

| Les écrans de bureau sont rendus en 1280px | Les écrans mobiles sont rendus en 390px |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## Points clés

- **Aperçu au survol.** Pointer une ligne affiche l'écran réel sur place — aucune vignette, rien à récupérer ailleurs.
- **À son propre viewport.** Une mise en page mobile s'affiche en 390px et une mise en page bureau en 1280px : ni tassement ni flou.
- **Fichiers autonomes.** Chaque écran est un seul fichier HTML qui s'ouvre dans le navigateur sans étape de build.
- **Filtrage à la frappe.** Recherche par titre, filtre par viewport, navigation par zone ; `/` place le curseur dans la recherche.
- **Clair et sombre.** La galerie suit le thème du système.

## Contenu

| Zone | Écrans |
| --- | ---: |
| Marginalia — page d'accueil | 94 |
| Console — aperçu | 25 |
| Console — clés | 18 |
| Console — analytique | 17 |
| Console — écrans | 12 |
| Console — design system | 21 |
| Console — journaux | 7 |
| Console — réglages | 13 |
| Console — MCP | 6 |
| Console — playground | 2 |
| Console — autres | 33 |
| **Total** | **248** |

## Viewports

| Viewport | Écrans | Largeur de rendu |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## Arborescence

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

## Utilisation

1. Ouvrez la [galerie en ligne](https://krcupro.github.io/ui-reference-screens/) — rien à installer.
2. Ou clonez le dépôt et ouvrez `index.html` directement :

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

Une entrée par écran :

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

## Remarques

- Les écrans sont des maquettes statiques. Toutes les valeurs affichées sont inventées à titre d'illustration : aucun compte, clé, hôte ou donnée personnelle réels n'y figure.
- Seule la typographie est chargée depuis Google Fonts par le réseau ; tout le reste est en ligne.
- Certains titres reviennent dans différents états : chargement, vide, erreur, premier lancement, dégradé.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">Galerie en ligne</a>
  &nbsp;·&nbsp;
  <a href="../../README.md">Retour au README principal</a>
</p>
