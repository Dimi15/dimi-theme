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
    "editor.fontLigatures": true,
    "editor.smoothScrolling": true,
    "terminal.integrated.fontFamily": "JetBrains Mono",
    "terminal.integrated.fontSize": 14.4,
    "terminal.integrated.smoothScrolling": true,
    "workbench.colorTheme": "Dimi Theme", // or variants
    "workbench.iconTheme": "Dimi Theme Icons",
    "workbench.list.smoothScrolling": true,
}
```

##### JetBrains Mono Font Download: https://www.jetbrains.com/lp/mono/

#

## Tweaks & Theming

If you want to play around with new colours, use the settings `workbench.colorCustomizations` and `editor.tokenColorCustomizations` in `settings.json` to customize the currently selected theme.

#### **Enable Italics**

```
"editor.tokenColorCustomizations": {
        "[Dimi Theme], [Dimi Theme (Dark)], [Dimi Theme (Darker)]": {
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
        "[Dimi Theme], [Dimi Theme (Dark)], [Dimi Theme (Darker)]": {
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

## Colour Palette

<details>

|                                                                                                                           |                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| ![#000000](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23000000.png) `#000000` | ![#8fbcbb](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%238fbcbb.png) `#8fbcbb` |
| ![#2e3440](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%232e3440.png) `#2e3440` | ![#ff5a5a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23ff5a5a.png) `#ff5a5a` |
| ![#3b4252](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%233b4252.png) `#3b4252` | ![#d08770](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23d08770.png) `#d08770` |
| ![#434c5e](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23434c5e.png) `#434c5e` | ![#ebcb8b](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23ebcb8b.png) `#ebcb8b` |
| ![#4c566a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%234c566a.png) `#4c566a` | ![#a3be8c](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23a3be8c.png) `#a3be8c` |
| ![#616e88](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23616e88.png) `#616e88` | ![#b48ead](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23b48ead.png) `#b48ead` |
| ![#5e81ac](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%235e81ac.png) `#5e81ac` | ![#d8dee9](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23d8dee9.png) `#d8dee9` |
| ![#81a1c1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%2381a1c1.png) `#81a1c1` | ![#e5e9f0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23e5e9f0.png) `#e5e9f0` |
| ![#88c0d0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%2388c0d0.png) `#88c0d0` | ![#eceff4](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme/%23eceff4.png) `#eceff4` |

<summary>Dimi Theme</summary>

</details>
<details>

<summary>Dimi Theme (Dark)</summary>

|                                                                                                                                |                                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| ![#000000](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23000000.png) `#000000` | ![#88c0d0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%238fbcbb.png) `#8fbcbb` |
| ![#242a36](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23242a36.png) `#242a36` | ![#bf616a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23bf616a.png) `#bf616a` |
| ![#2e3440](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%232e3440.png) `#2e3440` | ![#ff5a5a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23ff5a5a.png) `#ff5a5a` |
| ![#313848](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23313848.png) `#313848` | ![#c67d66](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23c67d66.png) `#c67d66` |
| ![#394254](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23394254.png) `#394254` | ![#d08770](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23d08770.png) `#d08770` |
| ![#424c60](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23424c60.png) `#424c60` | ![#e1c181](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23e1c181.png) `#e1c181` |
| ![#4c566a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%234c566a.png) `#4c566a` | ![#ebcb8b](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23ebcb8b.png) `#ebcb8b` |
| ![#57647e](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%2357647e.png) `#57647e` | ![#99b482](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%2399b482.png) `#99b482` |
| ![#616e88](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23616e88.png) `#616e88` | ![#a3be8c](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23a3be8c.png) `#a3be8c` |
| ![#5477a2](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%235477a2.png) `#5477a2` | ![#aa84a3](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23aa84a3.png) `#aa84a3` |
| ![#5e81ac](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%235e81ac.png) `#5e81ac` | ![#b48ead](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23b48ead.png) `#b48ead` |
| ![#7797b7](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%237797b7.png) `#7797b7` | ![#ced4df](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23ced4df.png) `#ced4df` |
| ![#81a1c1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%2381a1c1.png) `#81a1c1` | ![#d8dee9](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23d8dee9.png) `#d8dee9` |
| ![#85b2b1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%2385b2b1.png) `#85b2b1` | ![#dbdfe6](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23dbdfe6.png) `#dbdfe6` |
| ![#8fbcbb](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%238fbcbb.png) `#8fbcbb` | ![#e2e5ea](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23e2e5ea.png) `#e2e5ea` |
| ![#7eb6c6](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%237eb6c6.png) `#7eb6c6` | ![#eceff4](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-dark/%23eceff4.png) `#eceff4` |

</details>
<details>

<summary>Dimi Theme (Darker)</summary>

|                                                                                                                                  |                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| ![#000000](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23000000.png) `#000000` | ![#88c0d0](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%2388c0d0.png) `#88c0d0` |
| ![#1f2531](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%231f2531.png) `#1f2531` | ![#ff5a5a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23ff5a5a.png) `#ff5a5a` |
| ![#2e3440](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%232e3440.png) `#2e3440` | ![#bf616a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23bf616a.png) `#bf616a` |
| ![#2c3343](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%232c3343.png) `#2c3343` | ![#c17861](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23c17861.png) `#c17861` |
| ![#343d4f](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23343d4f.png) `#343d4f` | ![#d08770](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23d08770.png) `#d08770` |
| ![#3d475b](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%233d475b.png) `#3d475b` | ![#dcbc7c](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23dcbc7c.png) `#dcbc7c` |
| ![#525f79](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23525f79.png) `#525f79` | ![#ebcb8b](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23ebcb8b.png) `#ebcb8b` |
| ![#4c566a](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%234c566a.png) `#4c566a` | ![#94af7d](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%2394af7d.png) `#94af7d` |
| ![#616e88](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23616e88.png) `#616e88` | ![#a3be8c](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23a3be8c.png) `#a3be8c` |
| ![#4f729d](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%234f729d.png) `#4f729d` | ![#a57f9e](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23a57f9e.png) `#a57f9e` |
| ![#5e81ac](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%235e81ac.png) `#5e81ac` | ![#b48ead](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23b48ead.png) `#b48ead` |
| ![#7292b2](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%237292b2.png) `#7292b2` | ![#c9cfda](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23c9cfda.png) `#c9cfda` |
| ![#81a1c1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%2381a1c1.png) `#81a1c1` | ![#d6dae1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23d6dae1.png) `#d6dae1` |
| ![#80adac](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%2380adac.png) `#80adac` | ![#dde0e5](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23dde0e5.png) `#dde0e5` |
| ![#8fbcbb](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%238fbcbb.png) `#8fbcbb` | ![#d8dee9](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23d8dee9.png) `#d8dee9` |
| ![#79b1c1](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%2379b1c1.png) `#79b1c1` | ![#eceff4](https://raw.githubusercontent.com/Dimi15/dimi-theme/main/img/colourPalettes/dimiTheme-darker/%23eceff4.png) `#eceff4` |

</details>

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
6. Code/File ＞ Preferences ＞ File Icon Theme ＞ Dimi Theme Icons
