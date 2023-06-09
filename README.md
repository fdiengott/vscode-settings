# vscode-settings

## Extensions
| Name | Extension id | Installation command |
| -------------- | ------------ | ---------------- |
| alphabetical-sorter | ue.alphabetical-sorter | code --install-extension aaron-bond.better-comments |
| auto-rename-tag | formulahendry.auto-rename-tag | code --install-extension adam-watters.vscode-color-pick |
| bond.better-comments | aaron-bond.better-comments | code --install-extension christian-kohler.path-intellisense |
| code-spell-checker | streetsidesoftware.code-spell-checker | code --install-extension chrmarti.regex |
| color-highlight | naumovs.color-highlight | code --install-extension dbaeumer.vscode-eslint |
| es7-react-js-snippets | rodrigovallades.es7-react-js-snippets | code --install-extension dionmunk.vscode-notes |
| es7-react-js-snippets | woodreamz.es7-react-js-snippets | code --install-extension dqisme.sync-scroll |
| git-graph | mhutchie.git-graph | code --install-extension eamodio.gitlens |
| gitlens | eamodio.gitlens | code --install-extension esbenp.prettier-vscode |
| innerhtml | nicolasparada.innerhtml | code --install-extension formulahendry.auto-rename-tag |
| kohler.path-intellisense | christian-kohler.path-intellisense | code --install-extension Gruntfuggly.todo-tree |
| markdown-all-in-one | yzhang.markdown-all-in-one | code --install-extension liviuschera.noctis |
| material-icon-theme | PKief.material-icon-theme | code --install-extension mhutchie.git-graph |
| material-theme | zhuangtongfa.material-theme | code --install-extension mkxml.vscode-filesize |
| noctis | liviuschera.noctis | code --install-extension naumovs.color-highlight |
| partial-diff | ryu1kn.partial-diff | code --install-extension nicolasparada.innerhtml |
| prettier-vscode | esbenp.prettier-vscode | code --install-extension PKief.material-icon-theme |
| regex | chrmarti.regex | code --install-extension pranaygp.vscode-css-peek |
| remote-vscode | rafaelmaiolla.remote-vscode | code --install-extension rafaelmaiolla.remote-vscode |
| s.vscode-scss-formatter | sibiraj-s.vscode-scss-formatter | code --install-extension redhat.vscode-yaml |
| sync-scroll | dqisme.sync-scroll | code --install-extension rodrigovallades.es7-react-js-snippets |
| todo-tree | Gruntfuggly.todo-tree | code --install-extension ryu1kn.partial-diff |
| vscode-css-peek | pranaygp.vscode-css-peek | code --install-extension sibiraj-s.vscode-scss-formatter |
| vscode-eslint | dbaeumer.vscode-eslint | code --install-extension streetsidesoftware.code-spell-checker |
| vscode-filesize | mkxml.vscode-filesize | code --install-extension stylelint.vscode-stylelint |
| vscode-import-cost | wix.vscode-import-cost | code --install-extension tombonnike.vscode-status-bar-format-toggle |
| vscode-mdx | unifiedjs.vscode-mdx | code --install-extension ue.alphabetical-sorter |
| vscode-notes | dionmunk.vscode-notes | code --install-extension unifiedjs.vscode-mdx |
| vscode-status-bar-format-toggle | tombonnike.vscode-status-bar-format-toggle | code --install-extension wix.vscode-import-cost |
| vscode-stylelint | stylelint.vscode-stylelint | code --install-extension woodreamz.es7-react-js-snippets |
| vscode-yaml | redhat.vscode-yaml | code --install-extension yzhang.markdown-all-in-one |
| watters.vscode-color-pick | adam-watters.vscode-color-pick | code --install-extension zhuangtongfa.material-theme |
****
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

## .zshrc settings
```bash
# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:/usr/local/bin:$PATH

export NODE_EXTRA_CA_CERTS="/Users/fdiengot/.certs/ZscalerRootCertificate-2048-SHA256.pem"

# Path to your oh-my-zsh installation.
export ZSH="/Users/fdiengot/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
ZSH_THEME="amuse"

plugins=(
  git
  zsh-syntax-highlighting
  zsh-autosuggestions
)

HISTFILE="$HOME/.zsh_history"

source $ZSH/oh-my-zsh.sh

if [ -f ~/.bash_aliases ]; then
  . ~/.bash_aliases
fi

if [ -f ~/.bash_functions ]; then
  . ~/.bash_functions
fi

autoload -U add-zsh-hook
load-nvmrc() {
  if [[ -f .nvmrc && -r .nvmrc ]]; then
    nvm use
  elif [[ ($(nvm version) != $(nvm version default)) && ($PWD = /Users/$USERNAME) ]]; then
    echo "Reverting to nvm default version"
    nvm use default
fi }
add-zsh-hook chpwd load-nvmrc
load-nvmrc

export USERNAME="password"
export PASSWORD="<username>"
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```
## .bash_aliases
```bash
# [ohmyzsh built in aliases](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh)

# customized
alias la='ls -A'
alias ni='npm install'
alias home='cd && code .'
alias reload='source ~/.zshrc'

# git
alias gst='git status'
alias glo='git log --oneline'
alias gcm='git commit -m '
alias co='git checkout'
alias gcb='git checkout -b '
alias con=gcb
alias fetch='git fetch origin'
alias push='git push origin head'
alias pull='git pull'
alias hreset='git reset --hard'
alias revert='git reset --soft HEAD~1'

# takes a branch name of `feature/####/<component>/<description>`
# and gives prompts to execute: fix(CAMPFIRE-####): <MESSAGE>
gcmc() {
    TICKET=$(git branch --show-current | grep -Eo '\/[0-9]+\/' | grep -Eo '[0-9]+')
    MESSAGE=$1
    echo 'What type of commit is this (fix, feat, build, chore, ci, docs, style, refactor, perf, test)?'
    read TYPE
    echo 'Is it a breaking change (y/n)?'
    read IS_BREAKING
    if [[ $IS_BREAKING == "y" ]]
    then
        gcm "$TYPE(CAMPFIRE-$TICKET)!: $1"
    else
        gcm "$TYPE(CAMPFIRE-$TICKET): $1"
    fi
}

findFile() {
    find . -type d -name node_modules -prune -o -name .git -prune -o -iname $1 -print
}
```
