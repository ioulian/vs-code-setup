# vs-code-setup
List of plugins and settings that I use for Frontend Development

## Extensions

- [Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag)
- [Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag)
- [Bracket Pair Colorizer](https://github.com/CoenraadS/BracketPair)
- [Calculator](https://github.com/lixquid/vscode-calculator) (Useful when converting pixel values to rem or defining time by using seconds)
- [Code Spell Checker](https://github.com/streetsidesoftware/vscode-spell-checker)
- [DotENV](https://github.com/mikestead/vscode-dotenv)
- [EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)
- [ESLint](https://github.com/Microsoft/vscode-eslint)
- [Git History](https://github.com/DonJayamanne/gitHistoryVSCode)
- [GitHub](https://github.com/KnisterPeter/vscode-github)
- [gitignore](https://github.com/CodeZombieCH/vscode-gitignore)
- [GitLens -- Git supercharged](https://github.com/eamodio/vscode-gitlens)
- [HTMLHint](https://github.com/Microsoft/vscode-htmlhint)
- [Import Cost](https://github.com/wix/import-cost)
- [IntelliSense for CSS class names in HTML](https://github.com/Zignd/HTML-CSS-Class-Completion)
- [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown)
- [markdownlint](https://github.com/DavidAnson/vscode-markdownlint)
- [Material Theme](https://github.com/equinusocio/vsc-material-theme)
- [npm](https://github.com/Microsoft/vscode-npm-scripts)
- [Npm Dependency](https://github.com/leftstick/vscode-npm-dependency)
- [npm Dependency Links](https://github.com/herrmannplatz/npm-dependency-links)
- [npm Intellisense](https://github.com/ChristianKohler/NpmIntellisense)
- [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)
- [Prettier](https://github.com/prettier/prettier-vscode)
- [REST Client](https://github.com/Huachao/vscode-restclient.git)
- [Sass](https://github.com/robinbentley/vscode-sass-indented)
- [SCSS Intellisense](https://github.com/mrmlnc/vscode-scss)
- [Search node_modules](https://github.com/jasonnutter/vscode-search-node-modules)
- [stylelint](https://github.com/shinnn/vscode-stylelint)
- [Sublime Babel](https://github.com/joshpeng/Sublime-Babel-VSCode)
- [SVG Viewer](https://github.com/cssho/vscode-svgviewer)
- [TODO Highlight](https://github.com/wayou/vscode-todo-highlight)
- [TSLint](https://github.com/Microsoft/vscode-typescript-tslint-plugin)
- [VSCode React Refactor](https://github.com/planbcoding/vscode-react-refactor)
- [vscode-icons](https://github.com/vscode-icons/vscode-icons)
- [XML Tools](https://github.com/DotJoshJohnson/vscode-xml)

## Settings dump

This is the whole settings file, maybe some properties are not needed anymore

```json
// Place your settings in this file to overwrite the default settings
{
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "gitlens.historyExplorer.enabled": true,
  "workbench.colorTheme": "Material Theme",
  "materialTheme.fixIconsRunning": false,
  "editor.renderWhitespace": "all",
  "editor.cursorBlinking": "phase",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.minimap.renderCharacters": false,
  "editor.smoothScrolling": true,
  "terminal.external.osxExec": "iTerm.app",
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "cSpell.userWords": [
    "alexeev",
    "backstopjs",
    "behaviour",
    "behaviours",
    "bezier",
    "binded",
    "dhcp",
    "divs",
    "drupal",
    "e",
    "easings",
    "exif",
    "ffie",
    "gifsicle",
    "guetzli",
    "gulpif",
    "gzipped",
    "helvetica",
    "htaccess",
    "imgoptim",
    "intelephense",
    "intelli",
    "ioulian",
    "iñtërnâtiônàlizætiøn",
    "jank",
    "lucida",
    "metrix",
    "minification",
    "minified",
    "mstile",
    "optim",
    "optipng",
    "paginator",
    "pano",
    "ph",
    "phpcbf",
    "phpcs",
    "phpstorm",
    "pkgd",
    "pstorm",
    "quokka",
    "reactjs",
    "rect",
    "sense",
    "slint",
    "strpos",
    "strtolower",
    "stylelintrc",
    "svg's",
    "svgicon",
    "swiper",
    "symfony",
    "transpiler",
    "typeof",
    "uuid's",
    "verdana",
    "waxdev",
    "xcode",
    "xlink",
    "yandex",
    "yslow"
  ],
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "cSpell.allowCompoundWords": true,
  "prettier.eslintIntegration": true,
  "prettier.stylelintIntegration": true,
  "files.trimFinalNewlines": true,
  "extensions.ignoreRecommendations": true,
  "rest-client.enableTelemetry": false,
  "editor.wordWrapColumn": 120,
  "prettier.printWidth": 120,
  "git.enableSmartCommit": true,
  "phpcs.executablePath": "/usr/local/bin/phpcs",
  "phpcs.enable": false,
  "twigcs.executablePath": "/Users/ioulianalexeev/.composer/vendor/allocine/twigcs/bin/twigcs",
  "workbench.statusBar.feedback.visible": false,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "eslint.packageManager": "yarn",
  "html-css-class-completion.enableEmmetSupport": true,
  "html-css-class-completion.includeGlobPattern": "**/*.{css,html,twig}",
  "gitlens.advanced.telemetry.enabled": false,
  "code-runner.enableAppInsights": false,
  "search.followSymlinks": false,
  "javascript.updateImportsOnFileMove.enabled": "never",
  "javascript.validate.enable": false,
  "flow.pathToFlow": "${workspaceRoot}/node_modules/.bin/flow",
  "prettier.requireConfig": true,
  "prettier.parser": "flow",
  "explorer.confirmDragAndDrop": false,
  "window.zoomLevel": 0,
  "twigcs.enable": false,
  "twig-language-2.formatting": false,
  "prettier.tslintIntegration": true,
  "tslint.ignoreDefinitionFiles": true,
  "files.associations": {
    "*.css": "postcss"
  },
  "tslint.configFile": ".tslint.json",
  "workbench.iconTheme": "vscode-icons"
}
```

## Keyboard shortcuts

```json
// Place your key bindings in this file to overwrite the defaults
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
