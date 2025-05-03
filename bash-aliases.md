# bash aliases

Create the file `.zsh_aliases` in your home directory.

```bash
# [ohmyzsh built in aliases](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh)

# customized
alias la='ls -A'
alias ls='ls -F1G'
alias ni='npm install'
alias home='code ~'
alias reload='source ~/.zshrc'
alias op='code .'
alias cof='co $(gb | fzf)'
alias '..'='cd ..'
alias '.2'='cd ../..'
alias '.3'='cd ../../..'
alias '.4'='cd ../../../..'

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
alias gbc='git branch --show-current'

# takes a branch name of `feature/####/<component>/<description>`
# and gives prompts to execute: fix(CAMPFIRE-####): <MESSAGE>
gcmm() {
    TICKET=$(git branch --show-current | grep -Eo '\/[0-9]+\/' | grep -Eo '[0-9]+')
    HEAD=$1
    BODY=$2
    ALL_ARGS=("$@");
    REST=("${ALL_ARGS[@]:2}") # get all args after first 2
    echo 'What type of commit is this (fix, feat, build, chore, ci, docs, style, refactor, perf, test)?'
    read TYPE
    gcm "$TYPE(CAMPFIRE-$TICKET): $HEAD" -m $BODY $REST
}

findFile() {
    find . -type d -name node_modules -prune -o -name .git -prune -o -iname $1 -print
}

logit() {
  $@ 2>&1 | tee log.txt
}
```
