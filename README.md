# Hairline for Orca

A quiet light and dark theme for [Orca](https://www.onorca.dev): near-black surfaces, soft gray text and
hairline borders that sit just one step above the background. Inspired by the clean, low-chrome
look of modern AI code editors.

It ships:

- **Hairline Dark** app theme: workspace sidebar, tabs, chat, diffs, git decorations and code colors
- **Hairline Dark** terminal theme with a matching ANSI palette
- **Hairline Light** app and terminal themes: white editor, light-gray chrome, the same hairline borders and darker syntax colors that stay legible on white

## Palette (Dark)

| Role | Color |
| --- | --- |
| Canvas / sidebar | `#141414` |
| Editor surface | `#181818` |
| Workspace sidebar | `#111111` |
| Borders | `#242424` |
| Text | `#e4e4e4` |
| Secondary text | `#8c8c8c` |
| Keywords | `#82d2ce` |
| Strings | `#e394dc` |
| Functions | `#efb080` |
| Types / links | `#87c3ff` |
| Numbers / constants | `#ebc88d` |
| Properties | `#aa9bf5` |

## Palette (Light)

| Role | Color |
| --- | --- |
| Canvas / sidebar | `#f7f7f7` |
| Editor surface | `#ffffff` |
| Borders | `#e6e6e6` |
| Text | `#1f1f1f` |
| Secondary text | `#666666` |
| Keywords | `#0f7d78` |
| Strings | `#b0389f` |
| Functions | `#b35a00` |
| Types / links | `#0a6bc4` |

## Install

```sh
orca plugin install pcauhi/orca-hairline-theme
```

Then in Settings → Appearance pick **Hairline Dark** as the Dark theme and **Hairline Light** as
the Light theme (and the matching terminal themes). With Appearance on System, Orca follows macOS.

## Develop

```sh
orca plugin validate .
orca plugin dev watch .
```

## License

MIT
