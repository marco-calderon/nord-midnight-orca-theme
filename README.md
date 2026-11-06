# Nord Midnight for Orca

A darker take on the [Nord for Orca](https://github.com/stablyai/orca-plugins/tree/main/plugins/nord-theme) theme, with a matching light variant. It includes two themes:

- **Nord Midnight** (dark): Nord's text, syntax and accent colors on one deep background, `#1C1E21`, for the editor, sidebars, tabs, cards, menus and inputs.
- **Nord Midnight Light** (light): Nord's Snow Storm and Polar Night colors on one background, `#E5E9F0`, with syntax colors darkened so each one meets WCAG AA contrast (4.5:1).

## Install

In Orca, open Settings → Plugins, search for **Nord Midnight** and install it. Then choose **Nord Midnight** or **Nord Midnight Light** in Settings → Appearance.

## Colors

| Part | Nord Midnight | Nord Midnight Light |
| --- | --- | --- |
| Background (editor, sidebars, tabs, cards, menus, inputs) | `#1c1e21` | `#e5e9f0` |
| Text | `#eceff4` | `#2e3440` |
| Hover and selection | `#434c5e` / `#4c566a` | `#d8dee9` |
| Active tab underline | `#88c0d0` | `#5e81ac` |
| Your chat messages | `#2e3440` | `#d8dee9` |

Syntax colors in Nord Midnight Light:

| Scope | Color |
| --- | --- |
| Comments | `#4c566a` |
| Keywords | `#3b5e85` |
| Strings | `#577140` |
| Functions | `#0c7482` |
| Classes and types | `#1c7473` |
| Variables | `#2e3440` |
| Numbers | `#865b7f` |
| Constants | `#7f6614` |
| Tags | `#4b6c8c` |

## Develop

```sh
orca plugin validate .
orca plugin dev load .
```

## License

MIT. Based on Nord for Orca by Lovecast Inc.
