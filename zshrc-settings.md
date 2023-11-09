# zshrc settings

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
ZSH_THEME="minimalism"

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
