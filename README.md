# vscode-my-config

VS CODE | My settings and extensions

This is my personal settings and extensions for VS Code

## Extensions

### General

- WSL [Microsoft]
- APC Customize UI++ [drcika]
- Advanced-New_File [patbenatar]
- Brazilian Portuguese Code Spell Checker [Street Side Software]
- Code Spell Checker [Street Side Software]
- Code Runner [Jun Han]
- Codeium: AI Coding Autocomplete and Chat [Codeium]
- CodeSnap [adpyke]
- DataBase Client [Weijan Chen]
- MySQL [Weijan Chen]
- Dev Containers [Microsoft]
- Docker [Microsoft]
- DotENV [mikestead]
- EditorConfig for VS Code [EditorConfig]
- File Utils[Steffen Leistner]
- Git History [Don Jayamanne]
- IntelliCode [Microsoft]
- IntelliCode API Usage Examples [Microsoft]
- Live Server [Ritwick Dey]
- Live Share [Microsoft]
- Markdown All in One [Yu Zhang]
- Markdown PDF [yzane]
- Markdownlint [David Anson]
- Portuguese (Brazil) Language Pack [Microsoft]
- Prettier - Code formatter [Prettier]
- YAML [YAML]

### C/C++

- C/C++ [Microsoft]

### Java

- Language Support for Java(TM) [Red Hat]
- Debugger for Java [Microsoft]
- Test Runner for Java [Microsoft]
- Project Manager for Java [Microsoft]
- Maven for Java [Microsoft]

### JavaScript

- Auto Rename Tag [Jun Han]
- ES7+ React/Redux/React-Native snippets [dsznajder]
- JavaScript (ES6) code snippets [charalampos karypidis]
- NativeBase VS Code Extension [NativeBase]
- ESLint [Microsoft]
- HTML CSS Support [ecmel]
- Inline Parameters for VSCode [Liam Hammett]
- npm Intellisense [Christian Kohler]
- React Native Tools [Microsoft]
- REST Client [Huachao Mao]

### PHP

- Auto Rename Tag [Jun Han]
- HTML CSS Support [ecmel]
- Inline Parameters for VSCode [Liam Hammett]
- PHP Awesome Snippets [HakCorp]
- php cs fixer [junstyle]
- PHP Intelephense [Ben Mewburn]

### Python

- AutoDocstring Python Docstring Generator [Nils Werner]
- Black Formatter [Microsoft]
- Pylance [Microsoft]
- Python [Microsoft]
- Python Enviroment Manager [Don Jayamanne]

## Theme

- Min Theme [Miguel Solorio]
- Symbols [Miguel Solorio]

## Settings

Copy the settings.json file and place it in your project in the .vscode folder

```{
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 100,
    "files.trimTrailingWhitespace": true,

    "workbench.editor.limit.enabled": true,
    "workbench.editor.limit.value": 5,
    "workbench.colorTheme": "Min Dark",
    "workbench.iconTheme": "symbols",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.editor.editorActionsLocation": "titleBar",
    "workbench.activityBar.location": "hidden",
    "workbench.editor.labelFormat": "short",
    "workbench.sideBar.location": "right",
    "workbench.layoutControl.enabled": false,
    "workbench.tree.indent": 22,
    "workbench.tree.renderIndentGuides": "onHover",
    "workbench.colorCustomizations": {
        "activityBar.background": "#000000",
        "editor.background": "#000000",
        "sideBar.background": "#000000",
        "statusBar.background": "#000000",
        "titleBar.activeBackground": "#000000",
        "titleBar.inactiveBackground": "#000000",
        "editorGroupHeader.tabsBackground": "#000000",
        "tab.activeBorderTop": "#ffffff",
        "tab.inactiveBackground": "#000000",
        "tab.inactiveForeground": "#ffffff",
        "tab.inactiveBorderTop": "#ffffff",
        "sideBar.border": "#2c2c2c",
        "activityBar.foreground": "#ffffff"
    },

    "window.zoomLevel": 1,
    "window.titleBarStyle": "custom",
    "window.commandCenter": false,
    "window.menuBarVisibility": "toggle",

    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.fontFamily": "'Fira Code', monospace",
    "editor.suggestSelection": "recentlyUsed",
    "editor.renderLineHighlight": "gutter",
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.wordWrap": "on",
    "editor.inlineSuggest.enabled": true,
    "editor.semanticHighlighting.enabled": true,
    "editor.fontLigatures": true,
    "editor.smoothScrolling": true,
    "editor.minimap.enabled": false,
    "editor.parameterHints.enabled": true,
    "editor.rulers": [80, 120],
    "editor.lineHeight": 1.6,
    "editor.fontSize": 14,
    "editor.tabSize": 4,
    "editor.bracketPairColorization.enabled": true,
    "editor.scrollbar.verticalScrollbarSize": 0,
    "editor.stickyScroll.enabled": false,
    "editor.defaultFormatter": "vscode.json-language-features",
    "editor.suggest.insertMode": "replace",
    "editor.quickSuggestions": {
        "strings": "on"
    },

    "explorer.compactFolders": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,

    "terminal.integrated.fontFamily": "MesloLGS NF",
    "terminal.integrated.defaultLocation": "editor",
    "terminal.integrated.fontSize": 16,

    "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
    "liveServer.settings.useWebExt": true,
    "liveServer.settings.port": 5500,

    "yaml.schemas": {},
    "yaml.customTags": [],

    "breadcrumbs.enabled": false,
    "symbols.hidesExplorerArrows": false,

    "extensions.ignoreRecommendations": true,
    "code-runner.runInTerminal": true,
    "vsintellicode.modify.editor.suggestSelection": "disabled",
    "codeium.enableConfig": {
        "*": true,
        "code-runner-output": true
    },

    "apc.font.family": "Inter",

    "apc.electron": {
        "titleBarStyle": "hiddenInset",
        "height": 42
    },

    "apc.header": {
        "height": 32
    },
    "apc.listRow": {
        "height": 24
    },
    "apc.stylesheet": {
        ".titlebar-center": "display: none !important;",
        ".monaco-list-row": "border-radius: 4px;",
        ".pane-header": "padding: 0 8px",
        ".pane-body": "padding: 0px"
    },

    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[markdown]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[php]": {
        "editor.defaultFormatter": "junstyle.php-cs-fixer"
    },

    "php-cs-fixer.config": ".php-cs-fixer.php;.php-cs-fixer.dist.php;.php_cs;.php_cs.dist",
    "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
    "php-cs-fixer.allowRisky": true,
    "php-cs-fixer.autoFixBySemicolon": true,
    "php-cs-fixer.onsave": true,
    "php-cs-fixer.rules": "@PSR12",
    "editor.suggest.snippetsPreventQuickSuggestions": true,

    "[python]": {
        "diffEditor.ignoreTrimWhitespace": false,
        "editor.defaultFormatter": "ms-python.black-formatter",
        "editor.formatOnPaste": true,
        "editor.formatOnType": true,
        "editor.formatOnSave": true
    },
    "python.analysis.autoImportCompletions": true,
    "python.analysis.completeFunctionParens": true,
    "python.analysis.autoFormatStrings": true,
    "python.analysis.importFormat": "absolute",
    "black-formatter.importStrategy": "fromEnvironment",

    "cSpell.language": "en-US, PT-BR",
    "cSpell.userWords": [
        "bootcamp",
        "chakra",
        "checkin",
        "checkins",
        "clsx",
        "Codegen",
        "datadog",
        "Datetime",
        "dayjs",
        "Dotenv",
        "Elysia",
        "esbenp",
        "esbuild",
        "fastify",
        "Fastify",
        "feedbackwidget",
        "ffprobe",
        "Hasher",
        "Hono",
        "ilike",
        "IUGU",
        "jamjuree",
        "jupiter",
        "liveblocks",
        "LIVEBLOCKS",
        "Marguerita",
        "Meslo",
        "middlewares",
        "mixpanel",
        "monaco",
        "nestjs",
        "omni",
        "Omni",
        "Onboarded",
        "pallas",
        "postgres",
        "postgresql",
        "prefetch",
        "reactflow",
        "roboto",
        "rocketseat",
        "rotion",
        "rsxp",
        "Sandpack",
        "shiki",
        "skylab",
        "sqlite",
        "supergraph",
        "svgr",
        "sympla",
        "tabnine",
        "tailwindcss",
        "textblock",
        "tiptap",
        "trpc",
        "TRPC",
        "tsup",
        "unfollow",
        "Unfollow",
        "unform",
        "Unform",
        "unmark",
        "upsert",
        "Usuario",
        "WEBPUSH"
    ],
    "cSpell.enableFiletypes": [
        "!asciidoc",
        "!cpp",
        "!csharp",
        "!go",
        "!handlebars",
        "!haskell",
        "!jade",
        "!java",
        "!latex",
        "!php",
        "!pug",
        "!python",
        "!restructuredtext",
        "!rust",
        "!scala",
        "!scss"
    ]
    // "sonarlint.focusOnNewCode": true,
    // "tabnine.experimentalAutoImports": true,
    }

```
