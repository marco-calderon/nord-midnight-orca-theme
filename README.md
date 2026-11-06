# Nord Dark for Orca

A darker take on the [Nord for Orca](https://github.com/stablyai/orca-plugins/tree/main/plugins/nord-theme) theme. It keeps Nord's colors for text, syntax highlighting and accents, and uses one background, `#1C1E21`, for the editor, sidebars, tabs, cards, menus and inputs.

## Install

In Orca, open Settings → Plugins, search for **Nord Dark** and install it. Then choose **Nord Dark** in Settings → Appearance.

## Changes from Nord

| Token | Nord | Nord Dark |
| --- | --- | --- |
| Background, editor, sidebar, cards, popovers, inputs | `#2e3440` / `#292e39` / `#3b4252` | `#1c1e21` |
| Tab bar and tabs | derived from cards | `#1c1e21`, active tab marked by a `#88c0d0` underline |
| Your chat messages | derived | `#2e3440` |

## Develop

```sh
orca plugin validate .
orca plugin dev load .
```

## License

MIT. Based on Nord for Orca by Lovecast Inc.
