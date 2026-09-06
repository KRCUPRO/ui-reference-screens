<h1 align="center">Pantallas de referencia de UI</h1>

<p align="center">
  [English](../readme/README.en.md) | [한국어](../readme/README.ko.md) | [简体中文](../readme/README.zh.md) | [日本語](../readme/README.ja.md) | **Español** | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | [العربية](../readme/README.ar.md) | [हिन्दी](../readme/README.hi.md) • [📜 Registro de cambios](../changelog/CHANGELOG.es.md)
</p>

---

> 248 pantallas de referencia en HTML autónomo: una consola de operaciones de pasarela de API y una página de destino editorial.

### [▶ Galería en vivo](https://krcupro.github.io/ui-reference-screens/)

Explorar todas las pantallas en el navegador

## Cómo se ve

![Cómo se ve](../assets/gallery-demo.gif)

*Pasa el cursor por cualquier fila para previsualizar la pantalla real; filtra por título o viewport.*

| Las pantallas de escritorio se renderizan a 1280px | Las pantallas móviles se renderizan a 390px |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## Destacados

- **Vista previa al pasar el cursor.** Apuntar a una fila renderiza la pantalla real en el sitio: sin miniaturas y sin descargar nada de ningún otro lugar.
- **Cada una a su propio viewport.** Un diseño móvil se previsualiza a 390px y uno de escritorio a 1280px, así no se aplasta ni se ve borroso.
- **Archivos autónomos.** Cada pantalla es un único archivo HTML que se abre en el navegador sin compilar nada.
- **Filtrado mientras escribes.** Busca por título, acota por viewport y salta entre áreas; pulsa `/` para enfocar la búsqueda.
- **Claro y oscuro.** La galería sigue el tema del sistema.

## Contenido

| Área | Pantallas |
| --- | ---: |
| Marginalia — página de destino | 94 |
| Consola — resumen | 25 |
| Consola — claves | 18 |
| Consola — analítica | 17 |
| Consola — pantallas | 12 |
| Consola — sistema de diseño | 21 |
| Consola — registros | 7 |
| Consola — ajustes | 13 |
| Consola — MCP | 6 |
| Consola — playground | 2 |
| Consola — otros | 33 |
| **Total** | **248** |

## Viewports

| Viewport | Pantallas | Ancho renderizado |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## Estructura

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

## Cómo usarlo

1. Abre la [galería en vivo](https://krcupro.github.io/ui-reference-screens/): no hay nada que instalar.
2. O clónalo y abre `index.html` directamente:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

Una entrada por pantalla:

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

## Notas

- Las pantallas son maquetas estáticas. Todos los valores mostrados son inventados a modo de ilustración: no aparecen cuentas, claves, hosts ni datos personales reales.
- La tipografía se carga por red desde Google Fonts; todo lo demás va en línea.
- Algunos títulos se repiten en distintos estados: cargando, vacío, error, primer arranque, degradado.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">Galería en vivo</a> · <a href="../../README.md">Volver al README principal</a>
</p>
