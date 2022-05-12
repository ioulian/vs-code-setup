# vs-code-setup
List of plugins and settings that I use for Frontend Development

## Extensions

### Editor

- [EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [TODO Highlight](https://github.com/wayou/vscode-todo-highlight) (Possible duplicate with [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments))
- [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)
- [Red Hat Commons](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-commons)

### Code in general

- [Calculator](https://github.com/lixquid/vscode-calculator) (Nice to have)

### Character checks and tools

- [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)
- [Highlight Bad Chars](https://marketplace.visualstudio.com/items?itemName=wengerk.highlight-bad-chars)
- [HTML accented character converter](https://marketplace.visualstudio.com/items?itemName=enriquein.htmlentity-replacer)

### HTML

- [Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag)
- [Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag)
- [HTMLHint](https://github.com/Microsoft/vscode-htmlhint)

### JS/ES6/TS

- [Sublime Babel](https://github.com/joshpeng/Sublime-Babel-VSCode)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Prettier](https://github.com/prettier/prettier-vscode)
- [ESLint](https://github.com/Microsoft/vscode-eslint)

### CSS/SCSS/POSTCSS

- [Sass](https://github.com/robinbentley/vscode-sass-indented)
- [SCSS Intellisense](https://github.com/mrmlnc/vscode-scss)
- [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)

### Markdown

- [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown)
- [markdownlint](https://github.com/DavidAnson/vscode-markdownlint)

### Git

- [Git History](https://github.com/DonJayamanne/gitHistoryVSCode)
- [GitHub](https://github.com/KnisterPeter/vscode-github)
- [gitignore](https://github.com/CodeZombieCH/vscode-gitignore)
- [GitLens -- Git supercharged](https://github.com/eamodio/vscode-gitlens)

### NPM

- [npm](https://github.com/Microsoft/vscode-npm-scripts)
- [Npm Dependency](https://github.com/leftstick/vscode-npm-dependency)
- [npm Dependency Links](https://github.com/herrmannplatz/npm-dependency-links)
- [npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense)
- [Search node_modules](https://github.com/jasonnutter/vscode-search-node-modules)
- [Import Cost](https://github.com/wix/import-cost)

### Docs/Comments

- [Rewrap](https://marketplace.visualstudio.com/items?itemName=stkb.rewrap)

### Other languages

- [DotENV](https://github.com/mikestead/vscode-dotenv)
- [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)
- [XML Tools](https://github.com/DotJoshJohnson/vscode-xml)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [Drupal Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=marcostazi.VS-code-drupal)
- [Twig](https://marketplace.visualstudio.com/items?itemName=whatwedo.twig)
- [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)

### Frameworks

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

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
