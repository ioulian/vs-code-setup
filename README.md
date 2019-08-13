# vs-code-setup
List of plugins and settings that I use for Frontend Development

## Extensions

### HTML

- [Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag)
- [Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag)
- [HTMLHint](https://github.com/Microsoft/vscode-htmlhint)

### Git

- [Git History](https://github.com/DonJayamanne/gitHistoryVSCode)
- [GitHub](https://github.com/KnisterPeter/vscode-github)
- [gitignore](https://github.com/CodeZombieCH/vscode-gitignore)
- [GitLens -- Git supercharged](https://github.com/eamodio/vscode-gitlens)

### Markdown

- [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown)
- [markdownlint](https://github.com/DavidAnson/vscode-markdownlint)

### Code in general

- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [Calculator](https://github.com/lixquid/vscode-calculator) (Useful when converting pixel values to rem or defining time by using seconds)
- [Code Spell Checker](https://github.com/streetsidesoftware/vscode-spell-checker)

### Editor

- [EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)
- [Material Theme](https://github.com/equinusocio/vsc-material-theme)
- [REST Client](https://github.com/Huachao/vscode-restclient.git)
- [SVG Viewer](https://github.com/cssho/vscode-svgviewer)
- [vscode-icons](https://github.com/vscode-icons/vscode-icons)
- [TODO Highlight](https://github.com/wayou/vscode-todo-highlight)
- [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)
- [Nasc VSCode Touchbar](https://marketplace.visualstudio.com/items?itemName=felipe.nasc-touchbar)

### NPM

- [npm](https://github.com/Microsoft/vscode-npm-scripts)
- [Npm Dependency](https://github.com/leftstick/vscode-npm-dependency)
- [npm Dependency Links](https://github.com/herrmannplatz/npm-dependency-links)
- [npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense)
- [Search node_modules](https://github.com/jasonnutter/vscode-search-node-modules)
- [Import Cost](https://github.com/wix/import-cost)

### JS/ES6/TS

- [Sublime Babel](https://github.com/joshpeng/Sublime-Babel-VSCode)
- [TSLint](https://github.com/Microsoft/vscode-typescript-tslint-plugin)
- [VSCode React Refactor](https://github.com/planbcoding/vscode-react-refactor)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Typescript React code snippets](https://marketplace.visualstudio.com/items?itemName=infeng.vscode-react-typescript)

### CSS/SCSS/POSTCSS

- [Sass](https://github.com/robinbentley/vscode-sass-indented)
- [SCSS Intellisense](https://github.com/mrmlnc/vscode-scss)
- [IntelliSense for CSS class names in HTML](https://github.com/Zignd/HTML-CSS-Class-Completion)
- [vscode-styled-components](https://github.com/styled-components/vscode-styled-components)

### Linting

- [Prettier](https://github.com/prettier/prettier-vscode)
- [stylelint](https://github.com/shinnn/vscode-stylelint)
- [ESLint](https://github.com/Microsoft/vscode-eslint)

### Other

- [DotENV](https://github.com/mikestead/vscode-dotenv)
- [XML Tools](https://github.com/DotJoshJohnson/vscode-xml)

## Settings dump

This is the whole settings file, maybe some properties are not needed anymore

```json
{
    "workbench.colorTheme": "Material Theme High Contrast",
    "workbench.colorCustomizations": {
        "activityBarBadge.background": "#80CBC4",
        "list.activeSelectionForeground": "#80CBC4",
        "list.inactiveSelectionForeground": "#80CBC4",
        "list.highlightForeground": "#80CBC4",
        "scrollbarSlider.activeBackground": "#80CBC450",
        "editorSuggestWidget.highlightForeground": "#80CBC4",
        "textLink.foreground": "#80CBC4",
        "progressBar.background": "#80CBC4",
        "pickerGroup.foreground": "#80CBC4",
        "tab.activeBorder": "#80CBC4",
        "notificationLink.foreground": "#80CBC4",
        "editorWidget.resizeBorder": "#80CBC4",
        "editorWidget.border": "#80CBC4",
        "settings.modifiedItemIndicator": "#80CBC4",
        "settings.headerForeground": "#80CBC4",
        "panelTitle.activeBorder": "#80CBC4",
        "breadcrumb.activeSelectionForeground": "#80CBC4",
        "menu.selectionForeground": "#80CBC4",
        "menubar.selectionForeground": "#80CBC4",
        "editor.findMatchBorder": "#80CBC4",
        "selection.background": "#80CBC440"
    },
    "materialTheme.accent": "Teal",
    "workbench.iconTheme": "vscode-icons",
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    "editor.renderWhitespace": "all",
    "editor.formatOnSave": true,
    "terminal.external.osxExec": "iTerm.app",
    "eslint.autoFixOnSave": true,
    "explorer.confirmDragAndDrop": false,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "nasc-touchbar.addCursorBelow": false,
    "nasc-touchbar.goToDefinition": false,
    "nasc-touchbar.rename": false,
    "nasc-touchbar.showCommands": false,
    "nasc-touchbar.togglePanel": false,
    "nasc-touchbar.commentLine": true,
    "nasc-touchbar.toggleSidebar": true,
    "nasc-touchbar.blockComment": true,
    "nasc-touchbar.copyLineDown": true,
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}
```

## Keyboard shortcuts

```json
[
    {
        "key": "shift+cmd+d",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+down",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+cmd+e",
        "command": "calculator.replace"
    }
]
```
