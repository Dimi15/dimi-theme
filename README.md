# Dimi Theme

![Card Logo](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/themeLogo/cardLogo.png "Card Logo")

#

## Recommended Editor Settings

```
{
    "editor.fontFamily": "JetBrains Mono",
    "editor.cursorBlinking": "smooth",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.fontSize": 14.4,
    "editor.lineHeight": 1.5,
    "editor.scrollbar.verticalScrollbarSize": 0,
    "editor.scrollbar.horizontalScrollbarSize": 0,
    "editor.formatOnSave": true,
    "editor.fontLigatures": true,
    "editor.smoothScrolling": true,
    "editor.minimap.autohide": true,
    "editor.minimap.renderCharacters": false,

    "terminal.integrated.fontFamily": "JetBrains Mono",
    "terminal.integrated.fontSize": 14.4,
    "terminal.integrated.smoothScrolling": true,

    "workbench.colorTheme": "Dimi Theme", // or variants
    "workbench.statusBar.visible": false,
    "workbench.list.smoothScrolling": true,
    "workbench.layoutControl.enabled": false,

    "window.title": " ",
    "window.titleBarStyle": "custom",
    "window.menuBarVisibility": "compact",
    "window.commandCenter": false,
    "breadcrumbs.enabled": false,
}
```

##### JetBrains Mono Font Download: https://www.jetbrains.com/lp/mono/

#

## Colour Palette

|                                                                                                                          |                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| ![#000000](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23000000.png "#000000") `#000000` | ![#bf616a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23bf616a.png "#bf616a") `#bf616a` |
| ![#2e3440](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%232e3440.png "#2e3440") `#2e3440` | ![#d08770](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23d08770.png "#d08770") `#d08770` |
| ![#3b4252](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%233b4252.png "#3b4252") `#3b4252` | ![#ebcb8b](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23ebcb8b.png "#ebcb8b") `#ebcb8b` |
| ![#434c5e](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23434c5e.png "#434c5e") `#434c5e` | ![#8fbcbb](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%238fbcbb.png "#8fbcbb") `#8fbcbb` |
| ![#4c566a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%234c566a.png "#4c566a") `#4c566a` | ![#a3be8c](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23a3be8c.png "#a3be8c") `#a3be8c` |
| ![#616e88](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23616e88.png "#616e88") `#616e88` | ![#b48ead](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23b48ead.png "#b48ead") `#b48ead` |
| ![#5e81ac](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%235e81ac.png "#5e81ac") `#5e81ac` | ![#d8dee9](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23d8dee9.png "#d8dee9") `#d8dee9` |
| ![#81a1c1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%2381a1c1.png "#81a1c1") `#81a1c1` | ![#e5e9f0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23e5e9f0.png "#e5e9f0") `#e5e9f0` |
| ![#88c0d0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%2388c0d0.png "#88c0d0") `#88c0d0` | ![#eceff4](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalette/%23eceff4.png "#eceff4") `#eceff4` |

#

## Tweaks & Theming

If you want to play around with new colours, use the settings `workbench.colorCustomizations` and `editor.tokenColorCustomizations` in `settings.json` to customize the currently selected theme.

#### **Enable Italics**

```
"editor.tokenColorCustomizations": {
        "[Dimi Theme]": { // or variants
            "textMateRules": [
                {
                    "scope": [
                        "comment",
                        "keyword",
                        "keyword.operator.expression",
                        "storage",
                        "variable.language",
                        "support.function.construct.output.php"
                    ],
                    "settings": {
                        "fontStyle": "italic"
                    }
                },
                {
                    "scope": [
                        "keyword.operator",
                        "keyword.other.unit",
                        "storage.type.function.arrow.js"
                    ],
                    "settings": {
                        "fontStyle": ""
                    }
                }
            ]
        }
    }
```

#### **Enable Bold Keywords**

```
"editor.tokenColorCustomizations": {
        "[Dimi Theme]": { // or variants
            "textMateRules": [
                {
                    "scope": [
                        "keyword",
                        "keyword.operator.expression",
                        "storage",
                        "variable.language",
                        "support.function.construct.output.php"
                    ],
                    "settings": {
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": [
                        "keyword.operator",
                        "keyword.other.unit",
                        "storage.type.function.arrow.js"
                    ],
                    "settings": {
                        "fontStyle": ""
                    }
                }
            ]
        }
    }
```

#

## Contributing

See something strange? Please report [here](https://github.com/Dimi15/dimi-theme/issues). A screenshot would be great for clarification purposes.

#

## Installation

1. Open the extensions sidebar on Visual Studio Code
2. Search for Dimi Theme
3. Click Install to install it
4. Click Reload to reload your editor
5. Code/File ＞ Preferences ＞ Color Theme ＞ Dimi Theme
