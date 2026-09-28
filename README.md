# Borozdov Pebble

A theme from the Borozdov collection. Two faces — light **Overcast**, an editorial
broadsheet on warm stone, and dark **Basalt**, the same broadsheet after dark. A grey
parchment canvas for the chrome, a white paper sheet for the note, a serif display voice,
spaced sans body text, pill controls and zero shadows.

![Borozdov Pebble in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/pebble/main/screenshots/light.png)

![Borozdov Pebble in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/pebble/main/screenshots/dark.png)

## Principles

- **Paper on stone.** The side panels, tab bars and status bar are warm stone; the note is
  a white sheet laid on top, its edge the tab bar's outline. Panels inside the sheet are
  sand. Nothing casts a shadow — depth is a tonal shift and a hairline.
- **Serif against sans.** Pebble Serif announces the title and the two largest headings
  like pull-quotes; the platform's own sans carries the text with positive tracking, the
  editorial voice of the system.
- **Austere colour.** Ink fills a checked task, a toggle and the main button. Moss, a data
  colour, is allowed only for links and the highlighter.
- **Everything is a pill.** Buttons, tags and property values are pills with a stone edge;
  cards and fields keep 8px corners.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as sand panels with a stone edge and the title in the type's colour
- Pull quotes in the serif, a size up, behind an ink rule
- Tables as paper cards with a sand header band
- The open file in the sidebar sits on a white sheet
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Pebble**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/pebble/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Pebble/`, then choose Borozdov Pebble under
Settings → Appearance → Themes.

## Font

Pebble Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of
Merriweather (© 2020 The Merriweather Project Authors), renamed because a modified copy
may not use the original's Reserved Font Name. One weight, for the title, the two largest
headings and pull quotes only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Пасмурно» — газетная полоса
на тёплом камне, и тёмный «Базальт» — та же полоса после заката. Серый каменный холст для
интерфейса, белый бумажный лист для заметки, заголовки с засечками (Pebble Serif),
разреженный текст, кнопки-пилюли и ни одной тени. Устанавливается из каталога: Настройки →
Оформление → Темы → Настроить → Borozdov Pebble → Установить и применить.
