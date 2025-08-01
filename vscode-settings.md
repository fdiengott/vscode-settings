# vscode settings

This should live in the file settings.json which can be accessed through `⌘ ⇧ + p`, "Preferences: Open User Settings (JSON)

Make sure to download the "Cypher" extension for the color theming to look correct.

```json
{
  "extensions.autoUpdate": false,
  "telemetry.telemetryLevel": "off",
  "extensions.autoCheckUpdates": false,
  "git.ignoreLegacyWarning": true,
  "git.ignoreMissingGitWarning": true,
  "js/ts.implicitProjectConfig.checkJs": false,

  // minimap
  "editor.minimap.enabled": false,
  "editor.minimap.maxColumn": 80,
  "editor.minimap.side": "left",
  "editor.minimap.size": "fill",
  "editor.minimap.showSlider": "always",
  "editor.minimap.renderCharacters": false,
  "editor.rulers": [120],
  "editor.showFoldingControls": "always",
  "workbench.editor.tabSizing": "shrink",
  "workbench.list.horizontalScrolling": true,

  // desktop custom colorizing
  // "workbench.colorTheme": "Cypher",
  // "workbench.iconTheme": "material-icon-theme",

  "workbench.colorTheme": "Default High Contrast",
  "workbench.colorCustomizations": {
    "editorIndentGuide.background1": "bebcbc",
    "editorUnnecessaryCode.opacity": "#000000ca",
    "editorUnnecessaryCode.border": "#ffffff6c",
    "editor.lineHighlightBorder": "#f38518",
    "list.inactiveSelectionBackground": "#6dffb137",
    "editor.background": "#000000",
    // "editorCursor.foreground": "#c4c6c2",
    "editor.findMatchBackground": "#bb727242",
    "editor.findMatchBorder": "#fff5",
    "editor.findMatchHighlightBackground": "#924e4e60",
    "editor.findMatchHighlightBorder": "#ffffff22",
    "editor.lineHighlightBackground": "#343030",
    // "editor.selectionBackground": "#fcfdb030",
    // "editor.selectionHighlightBorder": "#fff2002f",
    "list.highlightForeground": "#f9b4ed",
    "list.inactiveSelectionBackground": "#6dffb137",
    "editor.hoverHighlightBackground": "#fff3",
    "tab.hoverForeground": "#fff",
    "panel.border": "#757a80",
    "panel.background": "#202020",
    "terminal.background": "#0a0a0a",
    "terminal.foreground": "#b5bcc6",
    "terminal.tab.activeBorder": "#ff0000",
    "minimapSlider.background": "#ffffff2f",
    "minimapSlider.hoverBackground": "#ffffff3f",
    "minimapGutter.addedBackground": "#00fa26",
    "minimapGutter.deletedBackground": "#ff0000",
    "minimapGutter.modifiedBackground": "#0073ff",
    "minimap.selectionHighlight": "#ffffe9ab",
    "minimap.warningHighlight": "#ffff0067",
    "statusBar.background": "#8fbcbb",
    "statusBar.noFolderBackground": "#8fbcbb",
    "statusBar.debuggingBackground": "#8fbcbb",
    "statusBar.foreground": "#000",
    "statusBar.debuggingForeground": "#000"
  },
  "window.title": "${activeEditorMedium} | ${rootPath}",
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "terminal.integrated.cursorStyle": "line",
  "editor.wordWrap": "on",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "explorer.compactFolders": false,
  "yaml.schemas": {
    "file:///Users/fdiengot/.vscode/extensions/atlassian.atlascode-2.9.1/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
  },
  "redhat.telemetry.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.defaultDateFormat": null,
  "gitlens.defaultDateShortFormat": "M/D/YY",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[astro]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[mdx]": {
    "editor.formatOnSave": false
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "html.format.unformatted": "",
  "json.schemas": [],
  "terminal.integrated.scrollback": 3000,
  "eslint.codeActionsOnSave.mode": "problems",
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "cSpell.userWords": [
    "astro",
    "borderless",
    "capslock",
    "classname",
    "classnames",
    "customfield",
    "datepicker",
    "datetime",
    "describedby",
    "DESLANG",
    "Diengott",
    "esbenp",
    "etrade",
    "Flexbox",
    "graphik",
    "gridline",
    "gridlines",
    "inputmode",
    "isnt",
    "labelledby",
    "Monokai",
    "multibar",
    "Nums",
    "precommit",
    "prepush",
    "rgba",
    "roboto",
    "stylelint",
    "testid",
    "typeof",
    "VALS",
    "VIEWBOX",
    "xeon"
  ],
  "emmet.excludeLanguages": ["markdown", "JavaScript"],
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  // Used to color regex
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      // custom colors
      {
        "scope": ["text.html.markdown"],
        "settings": {
          "foreground": "#7a9e8b"
        }
      },
      {
        "scope": ["variable", "markup.inline.raw", "support.class"],
        "settings": {
          "foreground": "#ff9ab8"
        }
      },
      {
        "scope": [
          // "support.class",
          "entity.name.function"
        ],
        "settings": {
          "foreground": "#78b6db"
        }
      },
      {
        "scope": ["source.css support.type.property-name"],
        "settings": {
          "foreground": "#8ec0dc"
        }
      },
      {
        "scope": ["keyword.control"],
        "settings": {
          "foreground": "#e4aabc"
        }
      },
      {
        "scope": [
          "storage.type",
          "meta.block variable.other.property",
          "variable.other.property",
          "meta.object-literal.key"
        ],
        "settings": {
          "foreground": "#d6c491"
        }
      },
      {
        "scope": ["comment", "punctuation.definition.comment"],
        "settings": {
          "foreground": "#B1B2B3",
          "fontStyle": "italic"
        }
      },
      {
        "scope": [
          "variable.other.readwrite",
          "entity.name.tag",
          "meta.tag.sgml",
          "markup.deleted.git_gutter",
          "meta.block variable.other",
          "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json",
          "markdown.heading",
          "markup.heading | markup.heading entity.name",
          "markup.heading.markdown punctuation.definition.heading.markdown",
          "variable.parameter"
        ],
        "settings": {
          "foreground": "#de940c"
        }
      },

      // regex
      {
        "scope": ["string.regexp"],
        "settings": {
          "foreground": "#65AAD1"
        }
      },
      {
        "scope": ["constant.other.character-class.regexp"],
        "settings": {
          "foreground": "#65e0d4"
        }
      },
      {
        "scope": [
          "punctuation.definition.group.regexp",
          "punctuation.definition.character-class.regexp"
        ],
        "settings": {
          "foreground": "#e5c07b"
        }
      },
      {
        "scope": [
          "meta.assertion.look-behind.regexp",
          "meta.assertion.negative-look-behind.regexp",
          "meta.assertion.look-ahead.regexp",
          "meta.assertion.negative-look-ahead.regexp"
        ],
        "settings": {
          "foreground": "#98C379"
        }
      },
      {
        "scope": [
          "punctuation.definition.string.begin",
          "punctuation.definition.string.end",
          "keyword.operator.or.regexp"
        ],
        "settings": {
          "foreground": "#b456c2"
        }
      }
    ]
  },
  // used to improve comments: TODOs and labeled./styled comments
  "todo-tree.highlights.defaultHighlight": {
    "foreground": "#fff",
    "background": "#cb00e6"
  },
  "todo-tree.highlights.customHighlight": {
    "LINK": {
      "icon": "link",
      "background": "#334bff",
      "foreground": "#fff"
    }
  },
  // "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^[ \\t]*(-|\\d+.))\\s*($TAGS)",
  "todo-tree.regex.regex": "(//|\\*|<!--)\\s+($TAGS)\\s+",
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "TEST",
    "INFO",
    "ASK"
  ],
  "todo-tree.filtering.excludedWorkspaces": ["docs_site/*, node_modules/*"],
  "better-comments.tags": [
    {
      "tag": "! ",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "? ",
      "color": "#61dcef",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "* ",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "> ",
      "color": "#fff381",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "TODO ",
      "color": "#cb00e6",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      // for documentation
      "tag": ": ",
      "color": "#cbdadf",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],
  "editor.linkedEditing": true,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "importCost.fontStyle": "italic",
  "importCost.smallPackageDarkColor": "#7F848E",
  "importCost.margin": 2,
  "importCost.bundleSizeDecoration": "compressed",
  "cssPeek.peekToExclude": ["**/node_modules/**", "**/dist/**"],
  "regex-previewer.enableCodeLens": false,
  "Notes.notesLocation": "/Users/fdiengot/code/notes",
  "scss.lint.duplicateProperties": "warning",
  "tabnine.experimentalAutoImports": true,
  "tabnine.debounceMilliseconds": 400,
  "audioCues.volume": 0,
  "editor.accessibilitySupport": "off",
  "material-icon-theme.files.color": "#26a69a",
  "editor.formatOnSave": true,
  "window.zoomLevel": 1,
  "editor.lineNumbers": "relative",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.cursorBlinking": "solid",
  "editor.colorDecorators": true,
  "workbench.editor.showTabs": "single",
  "workbench.statusBar.visible": "single",
  "workbench.sideBar.location": "right",
  "prettier.arrowParens": "avoid",
  "prettier.printWidth": 120,
  "prettier.tabWidth": 4,
  "prettier.trailingComma": "all",
  "prettier.useTabs": true,

  // vim
  "vim.foldfix": true,
  "vim.cursorStylePerMode.insert": "line",
  "vim.cursorStylePerMode.normal": "block",
  "vim.cursorStylePerMode.replace": "underline",
  "vim.leader": "<space>",
  "vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": ["n"],
      "after": ["n", "z", "z"]
    },
    {
      "before": ["N"],
      "after": ["N", "z", "z"]
    },
    {
      "before": ["c-d"],
      "after": ["c-d", "z", "z"]
    },
    {
      "before": ["c-u"],
      "after": ["c-u", "z", "z"]
    },
    {
      "before": ["s"],
      "commands": ["leap.find"]
    },
    {
      "before": ["y", "o", "r"],
      "commands": [":set rnu!"]
    },
    {
      "before": ["<leader>", "<leader>"],
      "commands": ["workbench.action.quickOpen"]
    },
    {
      "before": ["K"],
      "commands": ["editor.action.showHover"]
    },
    {
      "before": ["("],
      "after": ["^"]
    },
    {
      "before": [")"],
      "after": ["$"]
    },
    {
      "before": ["<leader>", "r", "n"],
      "commands": ["editor.action.rename"]
    },
    {
      "before": ["<leader>", "s", "w"],
      "after": ["v", "i", "w"],
      "commands": ["editor.action.findInFiles"]
    },
    {
      "before": ["<leader>", "s", "r"],
      "commands": [
        "workbench.action.quickOpenPreviousRecentlyUsedEditorInGroup"
      ]
    },
    {
      "before": ["g", "p", "t"],
      "commands": ["workbench.action.peekTypeDefinition"]
    },
    {
      "before": ["g", "t"],
      "commands": ["editor.action.goToTypeDefinition"]
    },
    {
      "before": ["<leader>", "r"],
      "commands": ["workbench.action.referenceSearch.trigger"]
    },
    {
      "before": ["g", "r"],
      "commands": ["editor.action.goToReferences"]
    },
    {
      "before": ["g", "k"],
      "commands": ["editor.action.showDefinitionPreviewHover"]
    },
    {
      "before": ["<leader>", "h", "r"],
      "commands": ["git.revertSelectedRanges"]
    },
    {
      "before": ["<leader>", "h", "s"],
      "commands": ["git.stage"]
    },
    {
      "before": ["<leader>", "k", "w"],
      "commands": ["workbench.action.closeEditorsInGroup"]
    },
    {
      "before": ["<leader>", "w", "+"],
      "commands": ["workbench.action.minimizeOtherEditors"]
    },
    {
      "before": ["<leader>", "w", "="],
      "commands": ["workbench.action.evenEditorWidths"]
    },
    {
      "before": ["]", "c"],
      "commands": ["editor.action.editor.nextChange"]
    },
    {
      "before": ["[", "c"],
      "commands": ["editor.action.editor.previousChange"]
    },
    {
      "before": ["]", "t"],
      "commands": ["todo-tree.goToNext"]
    },
    {
      "before": ["[", "t"],
      "commands": ["todo-tree.goToPrevious"]
    },
    {
      "before": ["]", "e"],
      "commands": ["editor.action.marker.next"]
    },
    {
      "before": ["[", "e"],
      "commands": ["editor.action.marker.previous"]
    },
    {
      "before": ["]", "x"],
      "commands": ["merge-conflict.next"]
    },
    {
      "before": ["[", "x"],
      "commands": ["merge-conflict.previous"]
    },
    {
      "before": ["]", "v"],
      "commands": ["workbench.aciton.compareEditor.nextChange"]
    },
    {
      "before": ["[", "v"],
      "commands": ["workbench.aciton.compareEditor.previousChange"]
    },
    {
      "before": ["<leader>", "b", "w"],
      "commands": ["workbench.action.files.save"]
    },
    {
      "before": ["<leader>", "p"],
      "commands": ["workbench.action.quickOpen"]
    },
    {
      "before": ["<leader>", "/"],
      "after": ["O", "/", "/", " ", "T", "O", "D", "O", "<ESC>"]
    },
    {
      "before": ["<leader>", "w", "k"],
      "commands": ["workbench.action.increaseViewSize"]
    },
    {
      "before": ["<leader>", "w", "j"],
      "commands": ["workbench.action.decreaseViewSize"]
    },
    {
      "before": ["<leader>", "g"],
      "commands": ["workbench.view.scm"]
    },
    {
      "before": ["<leader>", "t", "d"],
      "commands": ["workbench.view.extension.todo-tree-container"]
    },
    {
      "before": ["-"],
      "commands": ["workbench.view.explorer"]
    },
    {
      "before": ["<leader>", "o"],
      "commands": ["workbench.emmet.action.matchTag"]
    },
    {
      "before": ["<leader>", "c", "c"],
      "commands": ["merge-conflict.accept.current"]
    },
    {
      "before": ["<leader>", "c", "i"],
      "commands": ["merge-conflict.accept.incoming"]
    },
    {
      "before": ["<leader>", "c", "b"],
      "commands": ["merge-conflict.accept.both"]
    },
    {
      "before": ["<leader>", "v", "s"],
      "commands": ["workbench.action.splitEditorRight"]
    },
    {
      "before": ["<leader>", "s", "p"],
      "commands": ["workbench.action.splitEditorDown"]
    },
    {
      "before": ["<leader>", "r", "l"],
      "commands": [":set relativenumber!"]
    }
  ],
  "vim.insertModeKeyBindings": [
    {
      "before": ["j", "k"],
      "after": ["<ESC>"]
    }
  ],
  "vim.visualModeKeyBindings": [
    {
      "before": ["p"],
      "after": ["\"", "_", "d", "P"]
    }
  ],
  "vim.highlightedyank.enable": true,
  "vim.highlightedyank.color": "rgba(250, 240, 170, 0.5)",
  "vim.incsearch": true,
  "vim.handleKeys": {
    "<C-d>": true,
    "<C-j>": false,
    "<C-s>": false,
    "<C-z>": false
  },
  "vim.statusBarColorControl": true,
  "vim.statusBarColors.normal": ["#8fbcbb", "#000"],
  "vim.statusBarColors.insert": ["#bf616a", "#000"],
  "vim.statusBarColors.visual": ["#d48ecd", "#000"],
  "vim.statusBarColors.visualline": ["#d48ecd", "#000"],
  "vim.statusBarColors.visualblock": ["#a3de8c", "#000"],
  "vim.statusBarColors.replace": "#ea4545",
  "vim.statusBarColors.commandlineinprogress": "#007acc",
  "vim.statusBarColors.searchinprogress": "#007acc",
  "vim.statusBarColors.surroundinputmode": "#007acc",
  "vim.useSystemClipboard": true,

  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "breadcrumbs.enabled": false,
  "playwright.showTrace": false,
  "playwright.reuseBrowser": false
}
```
