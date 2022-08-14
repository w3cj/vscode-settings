# VS Code Settings

# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Themes/Color

* Current theme:
  * [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)
* Original theme I use in some videos:
  * [Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)
* I used this darker modification of the above theme for a few videos:
  * [Seti-Black](https://marketplace.visualstudio.com/items?itemName=bobsparadox.seti-black)

## Extensions

Most of the features of extensions I used to use are now built in to VS Code. These days I try to have as few extensions installed as possible, and only install extensions when I need them.

These are the extensions I have installed most of the time:

* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
  * Nice / colorful icons for many different file types
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.
* [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
  * Vue tooling
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Evaluate code/logs inline and show results in the editor

# Settings

```json
{
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/*.code-search": true
  },
  "search.useIgnoreFiles": false,
  "explorer.openEditors.visible": 0,
  "editor.linkedEditing": true,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "workbench.colorTheme": "Just Black",
  "workbench.iconTheme": "vscode-icons",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 24,
  "files.autoSave": "off",
  "editor.fontFamily": "Anonymous Pro",
  "markdown.preview.fontSize": 36,
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.minimap.enabled": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "html", "javascript"],
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "Vue.volar"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorCustomizations": {},
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "name": "envKeys",
        "scope": "string.quoted.double.env,source.env,constant.numeric.env",
        "settings": {
          "foreground": "#19354900"
        }
      }
    ]
  },
  "git.autofetch": true,
  "editor.lineHeight": 0,
  "editor.fontSize": 23,
  "window.zoomLevel": 2,
  "vsicons.dontShowNewVersionMessage": true,
  "extensions.ignoreRecommendations": true
}
```

# Keybindings

```json
[
  {
    "key": "cmd+1",
    "command": "workbench.action.openEditorAtIndex1"
  },
  {
    "key": "ctrl+1",
    "command": "-workbench.action.openEditorAtIndex1"
  },
  {
    "key": "cmd+2",
    "command": "workbench.action.openEditorAtIndex2"
  },
  {
    "key": "ctrl+2",
    "command": "-workbench.action.openEditorAtIndex2"
  },
  {
    "key": "cmd+3",
    "command": "workbench.action.openEditorAtIndex3"
  },
  {
    "key": "ctrl+3",
    "command": "-workbench.action.openEditorAtIndex3"
  },
  {
    "key": "cmd+4",
    "command": "workbench.action.openEditorAtIndex4"
  },
  {
    "key": "ctrl+4",
    "command": "-workbench.action.openEditorAtIndex4"
  },
  {
    "key": "cmd+5",
    "command": "workbench.action.openEditorAtIndex5"
  },
  {
    "key": "ctrl+5",
    "command": "-workbench.action.openEditorAtIndex5"
  },
  {
    "key": "cmd+6",
    "command": "workbench.action.openEditorAtIndex6"
  },
  {
    "key": "ctrl+6",
    "command": "-workbench.action.openEditorAtIndex6"
  },
  {
    "key": "cmd+7",
    "command": "workbench.action.openEditorAtIndex7"
  },
  {
    "key": "ctrl+7",
    "command": "-workbench.action.openEditorAtIndex7"
  },
  {
    "key": "cmd+8",
    "command": "workbench.action.openEditorAtIndex8"
  },
  {
    "key": "ctrl+8",
    "command": "-workbench.action.openEditorAtIndex8"
  },
  {
    "key": "cmd+9",
    "command": "workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+9",
    "command": "-workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+1",
    "command": "workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "cmd+1",
    "command": "-workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "ctrl+3",
    "command": "workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "cmd+3",
    "command": "-workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "ctrl+6",
    "command": "workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "cmd+6",
    "command": "-workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "ctrl+7",
    "command": "workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "cmd+7",
    "command": "-workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "ctrl+2",
    "command": "workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "cmd+2",
    "command": "-workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "ctrl+4",
    "command": "workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "cmd+4",
    "command": "-workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "ctrl+5",
    "command": "workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "cmd+5",
    "command": "-workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "ctrl+8",
    "command": "workbench.action.focusEighthEditorGroup"
  },
  {
    "key": "cmd+8",
    "command": "-workbench.action.focusEighthEditorGroup"
  }
]
```
