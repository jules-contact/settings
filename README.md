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
  // "workbench.colorTheme": "Tokyo Night",
  // "editor.fontLigatures": "'calt', 'ss01'",
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
          // "entity.name.function.ts",
          "meta.function-call.ts",
          // "source.ts",
          // "source.vue",
          // "string.quoted.double.html",
          // "meta.tag.block.any.html",
          "entity.other.attribute-name.html",
          // "text.html.vue-html",
          "storage.modifier",
          "storage.type.class.js",
          "storage.type.js"
        ],
        "settings": {
          "fontStyle": "italic bold",
          // "fontFamily": "Futura"
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
  // "prettier.enable": true,
  // Enable the flat config support

  "editor.defaultFormatter": "dbaeumer.vscode-eslint",
  "eslint.experimental.useFlatConfig": true,

  // Disable the default formatter
  "prettier.enable": false,

  // Auto fix
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true,
    "source.organizeImports": false
  },
  // Silent the stylistic rules in you IDE, but still auto fix them
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

  // The following is optional.
  // It's better to put under project setting `.vscode/settings.json`
  // to avoid conflicts with working with different eslint configs
  // that does not support all formats.

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
    "vue" // Add any other file extensions you want to lint
  ]
}
