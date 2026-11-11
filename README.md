# Hairline for Orca

A quiet dark theme for [Orca](https://www.onorca.dev): near-black surfaces, soft gray text and
hairline borders that sit just one step above the background. Inspired by the clean, low-chrome
look of modern AI code editors.

It ships:

- **Hairline Dark** app theme: workspace sidebar, tabs, chat, diffs, git decorations and code colors
- **Hairline Dark** terminal theme with a matching ANSI palette

## Palette

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

## Install

```sh
orca plugin install pcauhi/orca-hairline-theme
```

Then pick **Hairline Dark** in Settings → Appearance (Dark theme) and, for the terminal,
**Hairline Dark** as the terminal theme.

## Develop

```sh
orca plugin validate .
orca plugin dev watch .
```

## License

MIT
