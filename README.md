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

### Editor

- [EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)
- [Material Theme](https://github.com/equinusocio/vsc-material-theme)
- [TODO Highlight](https://github.com/wayou/vscode-todo-highlight)
- [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

### NPM

- [npm](https://github.com/Microsoft/vscode-npm-scripts)
- [Npm Dependency](https://github.com/leftstick/vscode-npm-dependency)
- [npm Dependency Links](https://github.com/herrmannplatz/npm-dependency-links)
- [npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense)
- [Search node_modules](https://github.com/jasonnutter/vscode-search-node-modules)
- [Import Cost](https://github.com/wix/import-cost)

### JS/ES6/TS

- [Sublime Babel](https://github.com/joshpeng/Sublime-Babel-VSCode)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)

### CSS/SCSS/POSTCSS

- [Sass](https://github.com/robinbentley/vscode-sass-indented)
- [SCSS Intellisense](https://github.com/mrmlnc/vscode-scss)

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
  "editor.formatOnPaste": true,
  "editor.renderWhitespace": "all",
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[ejs]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "explorer.confirmDelete": false,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "files.associations": {},
  "[twig]": {
    "editor.formatOnSave": false,
    "editor.formatOnPaste": false
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.format.enable": true,
  "explorer.confirmDragAndDrop": false
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
