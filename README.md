# settings

Mes paramètres Visual Studio Code 💻

```json
{
  "editor.suggestSelection": "first",
  "diffEditor.ignoreTrimWhitespace": false,
  "explorer.confirmDelete": false,
  "extensions.ignoreRecommendations": true,
  "editor.guides.bracketPairs": false,

  "files.associations": {
    "*.vue": "vue"
  },

  "files.exclude": {
    "**/.git": false
  },

  "svg.preview.mode": "svg",
  "editor.minimap.enabled": false,
  "editor.linkedEditing": true,
  "editor.suggest.insertMode": "replace",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "files.autoSave": "onFocusChange",
  "explorer.autoReveal": false,
  "explorer.confirmDragAndDrop": false,
  "workbench.tree.indent": 15,
  "emmet.triggerExpansionOnTab": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,

  // Style Parameters

  "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'",
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.lineHeight": 24,
  "editor.fontSize": 13,
  "material-icon-theme.hidesExplorerArrows": true,

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "keyword",
          "meta.function-call.ts",
          "entity.other.attribute-name.html",
          "storage.modifier",
          "storage.type.class.js",
          "storage.type.js"
        ],

        "settings": {
          "fontStyle": "italic bold",
        }
      },
      {
        "scope": [
          "keyword.control.conditional",
          "keyword.operator"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },

  "editor.wordWrap": "off",
  "diffEditor.wordWrap": "off",
  "editor.inlayHints.enabled": "off",
  "materialTheme.accent": "Pink",
  "workbench.colorTheme": "Material Theme Darker High Contrast",
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "settingsSync.ignoredSettings": [],
  "search.followSymlinks": false,
  "settingsSync.keybindingsPerPlatform": false,
  "workbench.iconTheme": "material-icon-theme",
  "vetur.validation.template": false,
  "vetur.validation.script": false,
  "vetur.validation.style": false,

  // Eslint Configuration

  "editor.defaultFormatter": "dbaeumer.vscode-eslint",
  "eslint.experimental.useFlatConfig": true,

  "prettier.enable": false,

  // Auto fix
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true,
    "source.organizeImports": false
  },

  // Silent the stylistic rules in IDE
  "eslint.rules.customizations": [
    { "rule": "@stylistic/*", "severity": "off" },
    { "rule": "style*", "severity": "off" },
    { "rule": "*-indent", "severity": "off" },
    { "rule": "*-spacing", "severity": "off" },
    { "rule": "*-spaces", "severity": "off" },
    { "rule": "*-order", "severity": "off" },
    { "rule": "*-dangle", "severity": "off" },
    { "rule": "*-newline", "severity": "off" },
    { "rule": "*quotes", "severity": "off" },
    { "rule": "*semi", "severity": "off" }
  ],

  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "vue",

    "html",
    "markdown",
    "json",
    "jsonc",
    "yaml"
  ],

  "[vue]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[json]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[html]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },

  "eslint.format.enable": true,

  "stylelint.validate": [
    "css",
    "scss",
    "vue"
  ]
}
```
