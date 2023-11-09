# bash aliases
Create the file `.zsh_aliases` in your home directory.

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
    echo 'Is it a breaking change (y/N)?'
    read IS_BREAKING
    if [[ $IS_BREAKING =~ ([yY]) ]]
    then
        gcm "$TYPE(CAMPFIRE-$TICKET): $1

BREAKING CHANGE: " $2
    else
        gcm "$TYPE(CAMPFIRE-$TICKET): $1" $2
    fi
}

findFile() {
    find . -type d -name node_modules -prune -o -name .git -prune -o -iname $1 -print
}
```
