# vscode-settings

## Extensions
- alphabetical-sorter:                 ue.alphabetical-sorter
- auto-rename-tag:                     formulahendry.auto-rename-tag
- bond.better-comments:                aaron-bond.better-comments
- code-spell-checker:                  streetsidesoftware.code-spell-checker
- color-highlight:                     naumovs.color-highlight
- es7-react-js-snippets:               rodrigovallades.es7-react-js-snippets
- es7-react-js-snippets:               woodreamz.es7-react-js-snippets
- git-graph:                           mhutchie.git-graph
- gitlens:                             eamodio.gitlens
- innerhtml:                           nicolasparada.innerhtml
- kohler.path-intellisense:            christian-kohler.path-intellisense
- markdown-all-in-one:                 yzhang.markdown-all-in-one
- material-icon-theme:                 PKief.material-icon-theme
- material-theme:                      zhuangtongfa.material-theme
- noctis:                              liviuschera.noctis
- partial-diff:                        ryu1kn.partial-diff
- prettier-vscode:                     esbenp.prettier-vscode
- regex:                               chrmarti.regex
- remote-vscode:                       rafaelmaiolla.remote-vscode
- s.vscode-scss-formatter:             sibiraj-s.vscode-scss-formatter
- sync-scroll:                         dqisme.sync-scroll
- todo-tree:                           Gruntfuggly.todo-tree
- vscode-css-peek:                     pranaygp.vscode-css-peek
- vscode-eslint:                       dbaeumer.vscode-eslint
- vscode-filesize:                     mkxml.vscode-filesize
- vscode-import-cost:                  wix.vscode-import-cost
- vscode-mdx:                          unifiedjs.vscode-mdx
- vscode-notes:                        dionmunk.vscode-notes
- vscode-status-bar-format-toggle:     tombonnike.vscode-status-bar-format-toggle
- vscode-stylelint:                    stylelint.vscode-stylelint
- vscode-yaml:                         redhat.vscode-yaml
- watters.vscode-color-pick:           adam-watters.vscode-color-pick

### Installation commands
code --install-extension aaron-bond.better-comments
code --install-extension adam-watters.vscode-color-pick
code --install-extension christian-kohler.path-intellisense
code --install-extension chrmarti.regex
code --install-extension dbaeumer.vscode-eslint
code --install-extension dionmunk.vscode-notes
code --install-extension dqisme.sync-scroll
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-rename-tag
code --install-extension Gruntfuggly.todo-tree
code --install-extension liviuschera.noctis
code --install-extension mhutchie.git-graph
code --install-extension mkxml.vscode-filesize
code --install-extension naumovs.color-highlight
code --install-extension nicolasparada.innerhtml
code --install-extension PKief.material-icon-theme
code --install-extension pranaygp.vscode-css-peek
code --install-extension rafaelmaiolla.remote-vscode
code --install-extension redhat.vscode-yaml
code --install-extension rodrigovallades.es7-react-js-snippets
code --install-extension ryu1kn.partial-diff
code --install-extension sibiraj-s.vscode-scss-formatter
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension stylelint.vscode-stylelint
code --install-extension tombonnike.vscode-status-bar-format-toggle
code --install-extension ue.alphabetical-sorter
code --install-extension unifiedjs.vscode-mdx
code --install-extension wix.vscode-import-cost
code --install-extension woodreamz.es7-react-js-snippets
code --install-extension yzhang.markdown-all-in-one
code --install-extension zhuangtongfa.material-theme

## vscode settings.json
```json
{
  "editor.minimap.maxColumn": 80,
  "editor.minimap.showSlider": "always",
  "editor.minimap.renderCharacters": false,
  "editor.minimap.size": "fit",
  "editor.rulers": [120],
  "editor.showFoldingControls": "always",
  "workbench.editor.tabSizing": "shrink",
  "workbench.list.horizontalScrolling": true,
  // desktop custom colorizing
  "workbench.colorTheme": "One Dark Pro Darker",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "editor.background": "#1c2432",
    "activityBar.background": "#1c2432",
    "activityBar.activeBackground": "#313d52",
    "activityBar.border": "#313d52",
    "sideBar.background": "#181b23",
    "sideBar.border": "#313d52",
    "terminal.background": "#171e29",
    "terminal.foreground": "#b5bcc6",
    "terminal.tab.activeBorder": "#ff0000"
  },
  "window.title": "${activeEditorMedium}${separator}${rootName}",
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "terminal.integrated.cursorStyle": "line",
  "editor.wordWrap": "on",
  "files.trimTrailingWhitespace": true,
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
  "window.zoomLevel": 1,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.formatOnSave": false
  },
  "[mdx]": {
    "editor.formatOnSave": false
  },
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "html.format.unformatted": "",
  "json.schemas": [],
  "todo-tree.highlights.defaultHighlight": {
    "foreground": "#fff",
    "background": "#cb00e6"
  },
  "terminal.integrated.scrollback": 3000,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "eslint.codeActionsOnSave.mode": "problems",
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "cSpell.userWords": [
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
    "VALS",
    "VIEWBOX",
    "xeon"
  ],
  "emmet.excludeLanguages": ["markdown", "JavaScript"],
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.formatOnSave": true,
  // Used to color regex
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["keyword.operator.or.regexp"],
        "settings": {
          "foreground": "#56B6C2"
        }
      },
      {
        "scope": ["punctuation.definition.group.regexp", "punctuation.definition.character-class.regexp"],
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
        "scope": ["punctuation.definition.string.begin.js", "punctuation.definition.string.end.js"],
        "settings": {
          "foreground": "#56B6C2"
        }
      }
    ]
  },
  // used to improve comments: TODOs and labeled./styled comments
  // "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^[ \\t]*(-|\\d+.))\\s*($TAGS)",
  "todo-tree.regex.regex": "(//|\\*|<!--)\\s+($TAGS)\\s+",
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "?",
    "*",
    ">",
    "!"
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
  "cssPeek.peekToExclude": [
    "**/node_modules/**",
    "**/dist/**"
  ],
  "regex-previewer.enableCodeLens": false,
  "Notes.notesLocation": "/Users/fdiengot/code/notes"
}
```
