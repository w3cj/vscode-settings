# VS Code Settings

# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

# Extensions

## Workflow

* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
  * Adds the ability to create files anywhere in your workspace.
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.
* [Toggle Quotes](https://marketplace.visualstudio.com/items?itemName=BriteSnow.vscode-toggle-quotes)
  * cmd ' (ctrl ' on win/linux) will cycle the first quote pair found (from the start/end of the section) between ', ", `

## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling

## Style/Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.

## Themes/Color

* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  * Matching parenthesis and curly brackets to with colors
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [Theme - Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)

## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Evaluate code/logs inline and show results in the editor
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code

# Settings

```json
{
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "workbench.colorTheme": "Seti Monokai",
  "window.zoomLevel": 2,
  "workbench.iconTheme": "eq-material-theme-icons",
  "editor.fontSize": 21,
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 16,
  "files.autoSave": "onFocusChange",
  "editor.fontFamily": "Anonymous Pro",
  "editor.tabSize": 2,
  "editor.lineHeight": 0,
  "workbench.colorCustomizations": {
      "activityBarBadge.background": "#C6FF00",
      "list.activeSelectionForeground": "#C6FF00",
      "list.inactiveSelectionForeground": "#C6FF00",
      "list.highlightForeground": "#C6FF00",
      "scrollbarSlider.activeBackground": "#C6FF0050",
      "editorSuggestWidget.highlightForeground": "#C6FF00",
      "textLink.foreground": "#C6FF00",
      "progressBar.background": "#C6FF00",
      "pickerGroup.foreground": "#C6FF00",
      "tab.activeBorder": "#C6FF00",
      "notificationLink.foreground": "#C6FF00"
  },
  "editor.minimap.enabled": false,
  "vsicons.projectDetection.disableDetect": true
}
```