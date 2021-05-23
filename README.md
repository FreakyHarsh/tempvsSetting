# tempvsSetting
{
  // --------------- Editor Settings ------------------------
  "editor.wordWrap": "on",
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.formatOnType": true,
  "editor.letterSpacing": 1,
  "editor.snippetSuggestions": "top",
  "javascript.validate.enable": false,
  "editor.fontSize": 17,
  //------------------- Language settings ----------------------------
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // --------------------- GIT settings -----------------------
  "git.enableSmartCommit": true,
  "git.autofetch": true,
  // -------------------------- SASS/CSS settings -------------------------
  "liveSassCompile.settings.includeItems": [
    "./css/custom/**.scss",
  ],
  "liveSassCompile.settings.formats": [
    // {
    //   "format": "compressed",
    //   "extensionName": ".min.css",
    //   "savePath": "/css"
    // },
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/dist"
    }
  ],
  "liveSassCompile.settings.generateMap": false,
  "css.remoteStyleSheets": [
    "https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css"
  ],
  // ----------------------- FLUTTER/DART SETTINGS -------------------
  "dart.previewFlutterUiGuides": true,
  "debug.openDebug": "openOnDebugBreak",
  "[dart]": {
    "editor.rulers": [
      80
    ],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  // ----------------- ES lint + prettier -----------------------
  "prettier.tabWidth": 2,
  "prettier.useTabs": false,
  "prettier.semi": true,
  "prettier.singleQuote": false,
  "prettier.jsxSingleQuote": false,
  "prettier.bracketSpacing": true,
  "prettier.jsxBracketSameLine": true,
  "prettier.arrowParens": "avoid",
  "prettier.printWidth": 160,
  "prettier.trailingComma": "none",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  // ----------- FORMATTERS SETTINGS ----------------
  "html.format.endWithNewline": true,
  "markdown-preview-enhanced.automaticallyShowPreviewOfMarkdownBeingEdited": true,
  "liveServer.settings.donotVerifyTags": true,
  "editor.autoClosingBrackets": "always",
  "liveServer.settings.donotShowInfoMsg": true,
  "workbench.startupEditor": "newUntitledFile",
  "files.autoSave": "afterDelay",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "peacock.favoriteColors": [
    {
      "name": "Angular Red",
      "value": "#dd0531"
    },
    {
      "name": "Azure Blue",
      "value": "#007fff"
    },
    {
      "name": "JavaScript Yellow",
      "value": "#f9e64f"
    },
    {
      "name": "Mandalorian Blue",
      "value": "#1857a4"
    },
    {
      "name": "Node Green",
      "value": "#215732"
    },
    {
      "name": "React Blue",
      "value": "#61dafb"
    },
    {
      "name": "Something Different",
      "value": "#832561"
    },
    {
      "name": "Svelte Orange",
      "value": "#ff3d00"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ],
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "workbench.iconTheme": "material-icon-theme",
  "markdown.preview.fontSize": 31,
  "indentRainbow.colors": [
    "rgba(255,255,64,0.07)",
    "rgba(127,255,127,0.07)",
    "rgba(255,127,255,0.07)",
    "rgba(79,236,236,0.07)"
  ],
  "indentRainbow.indentSetter": {},
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "editor.suggestSelection": "first",
  "indentRainbow.ignoreErrorLanguages": [
    "markdown",
  ],
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "auto-rename-tag.activationOnLanguage": [
    "*"
  ],
  "editor.multiCursorModifier": "ctrlCmd",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "yaml.schemas": {
    "file:///home/freakyharsh/.vscode/extensions/atlassian.atlascode-2.8.6/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "python.languageServer": "Microsoft",
  "tabnine.experimentalAutoImports": true,
  "python.autoComplete.extraPaths": [
    "./env/bin/python3.7"
  ],
  "python.linting.enabled": true,
  "python.envFile": "{workspaceFolder}\\<project>.env",
  "files.associations": {
    "*.html": "html"
  },
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "workbench.editorAssociations": [
    {
      "viewType": "jupyter.notebook.ipynb",
      "filenamePattern": "*.ipynb"
    }
  ],
  "terminal.integrated.shell.linux": "/bin/zsh",
  "terminal.integrated.shell.osx": "/bin/zsh",
  // "terminal.integrated.profiles.osx": "/bin/zsh",
  // "terminal.integrated.defaultProfile.linux": "/bin/zsh",
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "terminal.integrated.fontSize": 15,
  "workbench.sideBar.location": "right",
  "[scss]": {
    "editor.defaultFormatter": "sibiraj-s.vscode-scss-formatter"
  },
  "workbench.colorTheme": "Night Owl",
  "turboConsoleLog.includeFileNameAndLineNum": false,
  "turboConsoleLog.wrapLogMessage": true,
  "turboConsoleLog.addSemicolonInTheEnd": true,
  "turboConsoleLog.delimiterInsideMessage": ">>>",
}
