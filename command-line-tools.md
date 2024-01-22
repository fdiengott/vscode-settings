# Tools

| Tool    | Description                       | Link                                    |
| ------- | --------------------------------- | --------------------------------------- |
| exa     | adds colors to `ls`               | <https://github.com/ogham/exa>          |
| bat     | adds syntax highlighting to `cat` | <https://github.com/sharkdp/bat>        |
| ripgrep | improves `grep`                   | <https://github.com/BurntSushi/ripgrep> |
| fzf     | fuzzy finder, finds files         | <https://github.com/junegunn/fzf>       |
| zoxide  | improves `cd`                     | <https://github.com/ajeetdsouza/zoxide> |

## Things to consider implementing

entr - <https://github.com/eradman/entr>
mc - <https://midnight-commander.org/>

## Examples

### bat

`batcat {filename}`
`head {filename} | batcat`

### ripgrep

`rg {string}`
`rg -i {string}`
`rg --glob 'src/*.js' {string}`
`rg --glob 'src/**/*.js' {string}`

### fzf

`zfz` # opens up fuzzy finding window where you can start typing in

### zoxide

> `z code/charts` # adds charts to memory
> `z` # return to home directory
> `z charts` # can now type in part of path that's visited before to nav to it

