# Custom Theme
create the following file: /Users/diengott/.oh-my-zsh/custom/themes/minimalism.zsh-theme

```bash
# In zsh, % and ) are special characters. The fg signifies the foreground color. The %3~ shows the path of the current working directory at three levels depth. If you prefer the full path relative to the home directory to be shown you can update it to %0~. The (git_prompt_info) points towards the currently checked out git branch for the repository

# %n - username
# %m - host name
# %1~ - current directory. The number references number of files down
# %T - time in 24-hour format
# %* - time in 24-hour format with seconds
# %t - time in AM/PM or 12-hour format

# STYLING
# %B ... %b  --- bold
# %U ... %u  --- underline
# %S ... %s  --- highlighted
# %F{color} ... %f  --- change foreground
# %K{color} ... %k  --- change background

# Black: 0, 0, 0
# Red: 229, 34, 34
# Green: 166, 227, 45
# Yellow: 252, 149, 30
# Blue: 196, 141, 255
# Magenta: 250, 37, 115
# Cyan: 103, 217, 240
# White: 242, 242, 242


# The prompt

PROMPT='
%F{magenta}> %f'

# The right-hand prompt

# RPROMPT='[%F{#e9799b}%c%f]%S%F{#D6C491}%*%f%s%{$fg[magenta]%}$(git_prompt_info)$(git_prompt_status)%{$reset_color%}$(git_prompt_ahead)%{$reset_color%}'
# RPROMPT='[%F{#e9799b}%c%f]%S%F{#D6C491}%*%f%s%{$fg[magenta]%}%F{#6cc1f3}%40>…>$(current_branch)%>>%f'
RPROMPT='[%F{#e9799b}%c%f]%S%F{#D6C491}%*%f%s%{$fg[magenta]%}%F{#6cc1f3}${$(current_branch)[14,-1]}%f'

ZSH_THEME_GIT_PROMPT_PREFIX="%F{#6cc1f3}"
ZSH_THEME_GIT_PROMPT_SUFFIX="%f"
# ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg[cyan]%}"
# ZSH_THEME_GIT_PROMPT_SUFFIX="%{$reset_color%}"
# ZSH_THEME_GIT_PROMPT_DIRTY="%{$fg[yellow]%} ☂" # Ⓓ
# ZSH_THEME_GIT_PROMPT_UNTRACKED="%{$fg[cyan]%} ✭" # ⓣ
# ZSH_THEME_GIT_PROMPT_CLEAN="%{$fg[green]%} ☀" # Ⓞ

# ZSH_THEME_GIT_PROMPT_ADDED="%{$fg[cyan]%} ✚" # ⓐ ⑃
# ZSH_THEME_GIT_PROMPT_MODIFIED="%{$fg[yellow]%} ⚡"  # ⓜ ⑁
# ZSH_THEME_GIT_PROMPT_DELETED="%{$fg[red]%} ✖" # ⓧ ⑂
# ZSH_THEME_GIT_PROMPT_RENAMED="%{$fg[blue]%} ➜" # ⓡ ⑄
# ZSH_THEME_GIT_PROMPT_UNMERGED="%{$fg[magenta]%} ♒" # ⓤ ⑊
# ZSH_THEME_GIT_PROMPT_AHEAD="%{$fg[blue]%} 𝝙"

# ZSH_THEME_RUBY_PROMPT_PREFIX="%{$fg[yellow]%}"
# ZSH_THEME_RUBY_PROMPT_SUFFIX="%{$reset_color%}"

# More symbols to choose from:
# ☀ ✹ ☄ ♆ ♀ ♁ ♐ ♇ ♈ ♉ ♚ ♛ ♜ ♝ ♞ ♟ ♠ ♣ ⚢ ⚲ ⚳ ⚴ ⚥ ⚤ ⚦ ⚒ ⚑ ⚐ ♺ ♻ ♼ ☰ ☱ ☲ ☳ ☴ ☵ ☶ ☷
# ✡ ✔ ✖ ✚ ✱ ✤ ✦ ❤ ➜ ➟ ➼ ✂ ✎ ✐ ⨀ ⨁ ⨂ ⨍ ⨎ ⨏ ⨷ ⩚ ⩛ ⩡ ⩱ ⩲ ⩵  ⩶ ⨠
# ⬅ ⬆ ⬇ ⬈ ⬉ ⬊ ⬋ ⬒ ⬓ ⬔ ⬕ ⬖ ⬗ ⬘ ⬙ ⬟  ⬤ 〒 ǀ ǁ ǂ ĭ Ť Ŧ
# ╭ ╰ ─
```
