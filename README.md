# vs-code-setup
List of plugins and settings that I use for Frontend Development

## Extensions

### Editor

- [EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)
- [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [filesize](https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

#### General editor settings

```json
{
  "telemetry.telemetryLevel": "off",
  "explorer.confirmDragAndDrop": false,
  "editor.formatOnSave": true,
  "explorer.confirmDelete": false,
  "editor.formatOnPaste": false,
  "editor.renderWhitespace": "all",
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "search.useIgnoreFiles": true,
  "problems.showCurrentInStatus": true,
}
```

### Code in general

- [Calculator](https://github.com/lixquid/vscode-calculator) (Nice to have)

### Character checks and tools

- [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)
```json
{
  "gremlins.showInProblemPane": true,
}
```
- [Highlight Bad Chars](https://marketplace.visualstudio.com/items?itemName=wengerk.highlight-bad-chars)
- [HTML accented character converter](https://marketplace.visualstudio.com/items?itemName=enriquein.htmlentity-replacer)

### HTML

- [Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag)
- [Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag)

### JS/ES6/TS

- [Prettier](https://github.com/prettier/prettier-vscode)
```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
}
```
- [ESLint](https://github.com/Microsoft/vscode-eslint)
```json
{
  "eslint.format.enable": true,
}
```

### CSS/SCSS/POSTCSS

- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)

### Git

- [Git History](https://github.com/DonJayamanne/gitHistoryVSCode)
- [GitHub](https://github.com/KnisterPeter/vscode-github)
- [gitignore](https://github.com/CodeZombieCH/vscode-gitignore)
- [GitLens -- Git supercharged](https://github.com/eamodio/vscode-gitlens)

### NPM

- [npm Dependency Links](https://github.com/herrmannplatz/npm-dependency-links)
- [npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense)
- [Search node_modules](https://github.com/jasonnutter/vscode-search-node-modules)
- [Import Cost](https://github.com/wix/import-cost)

### Docs/Comments

- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [TODO Highlight](https://github.com/wayou/vscode-todo-highlight) (Possible duplicate with [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments))

### Other languages

- [DotENV](https://github.com/mikestead/vscode-dotenv)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

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
