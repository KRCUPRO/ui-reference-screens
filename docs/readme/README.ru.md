<h1 align="center">Референсные UI-экраны</h1>

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
  <a href="../readme/README.fr.md">Français</a>
  &nbsp;|&nbsp;
  <b>Русский</b>
  &nbsp;|&nbsp;
  <a href="../readme/README.ar.md">العربية</a>
  &nbsp;|&nbsp;
  <a href="../readme/README.hi.md">हिन्दी</a>
  &nbsp;•&nbsp;
  <a href="../changelog/CHANGELOG.ru.md">📜 История изменений</a>
</p>

---

> 248 автономных HTML-экранов: консоль эксплуатации API-шлюза и редакционная посадочная страница.

### [▶ Живая галерея](https://krcupro.github.io/ui-reference-screens/)

Посмотреть все экраны в браузере

## Как это выглядит

![Как это выглядит](../assets/gallery-demo.gif)

*Наведите курсор на строку, чтобы увидеть настоящий экран; фильтруйте по названию или вьюпорту.*

| Десктопные экраны рендерятся в 1280px | Мобильные экраны рендерятся в 390px |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## Особенности

- **Предпросмотр по наведению.** Наведение на строку рендерит настоящий экран на месте — без миниатюр и без загрузки чего-либо со стороны.
- **Каждый в своём вьюпорте.** Мобильная вёрстка показывается в 390px, десктопная — в 1280px, поэтому ничего не схлопывается и не размывается.
- **Самодостаточные файлы.** Каждый экран — один HTML-файл, открывается в браузере без сборки.
- **Фильтрация по мере ввода.** Поиск по названию, фильтр по вьюпорту, переходы между разделами; `/` ставит фокус в поиск.
- **Светлая и тёмная тема.** Галерея следует системной теме.

## Состав

| Раздел | Экранов |
| --- | ---: |
| Marginalia — лендинг | 94 |
| Консоль — обзор | 25 |
| Консоль — ключи | 18 |
| Консоль — аналитика | 17 |
| Консоль — экраны | 12 |
| Консоль — дизайн-система | 21 |
| Консоль — логи | 7 |
| Консоль — настройки | 13 |
| Консоль — MCP | 6 |
| Консоль — песочница | 2 |
| Консоль — прочее | 33 |
| **Всего** | **248** |

## Вьюпорты

| Вьюпорт | Экранов | Ширина рендера |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## Структура

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

## Как пользоваться

1. Откройте [живую галерею](https://krcupro.github.io/ui-reference-screens/) — устанавливать ничего не нужно.
2. Либо склонируйте репозиторий и откройте `index.html` напрямую:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

По одной записи на экран:

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

## Примечания

- Экраны — статические макеты. Все показанные значения выдуманы для наглядности: реальных аккаунтов, ключей, хостов и персональных данных в них нет.
- По сети подгружается только типографика из Google Fonts; всё остальное встроено.
- Некоторые названия повторяются в разных состояниях: загрузка, пусто, ошибка, первый запуск, деградация.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">Живая галерея</a>
  &nbsp;·&nbsp;
  <a href="../../README.md">Вернуться к основному README</a>
</p>
