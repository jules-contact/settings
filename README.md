# settings

Mes paramètres Visual Studio Code 💻

```json
{
    // VSCode
    "editor.suggestSelection": "first",
    "editor.minimap.enabled": false,
    "editor.acceptSuggestionOnCommitCharacter": false,
    "emmet.triggerExpansionOnTab": true,
    "editor.accessibilitySupport": "off",
    "explorer.confirmDragAndDrop": false,
    "git.confirmSync": false,
    "files.autoSave": "onFocusChange",
    "emmet.syntaxProfiles": {
        "vue-html": "html",
        "vue": "html"
    },
    
    // WorkBench
    "workbench.tree.indent": 15, 
    "workbench.activityBar.location": "top",
    "workbench.iconTheme": "material-icon-theme",
    
    // Editor
    "editor.wordWrap": "off",
    "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'",
    "editor.fontFamily": "Cascadia Code, Consolas, 'Courier New', monospace",
    "editor.lineHeight": 20,
    "editor.fontSize": 13,
    
    // Theme
    "materialTheme.accent": "Pink",
    "material-icon-theme.folders.theme": "specific",
    "material-icon-theme.hidesExplorerArrows": true,
    "vue.server.hybridMode": true,
    "workbench.colorTheme": "Material Theme High Contrast",
    // "editor.suggest.snippetsPreventQuickSuggestions": true,
    // "emmet.showSuggestionsAsSnippets": false,


  // Auto fix
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "always",
    "source.fixAll.stylelint": "always",
    "source.organizeImports": "never"
  },
  
    // Editor
 
    "[vue]": {
      "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "[json]": {
      "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "[jsonc]": {
      "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "[html]": {
      "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "css.validate": false,
    "less.validate": false,
    "scss.validate": false,
   
    // ESLint
    "eslint.experimental.useFlatConfig": true,
    "eslint.format.enable": true,
    "eslint.rules.customizations": [
      { "rule": "style/*", "severity": "off" },
      { "rule": "format/*", "severity": "off" },
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
      "yaml",
      "toml"
    ],
   
    // StyleLint
    "stylelint.enable": true,
    "stylelint.validate": [
      "css",
      "less",
      "postcss",
      "scss",
      "sass",
      "vue"
    ],
    "stylelint.snippet": [
      "css",
      "less",
    ]
}
```
