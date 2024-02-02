# vimrc
Create the file `.vimrc` in your home directory.

```
set number
set cursorline
set incsearch
set ignorecase
set smartcase

syntax on

" have command-line completion <Tab> (for filenames, help topics, option names)
" first list the available options and complete the longest common part, then
" have further <Tab>s cycle through the possibilities:
set wildmode=list:longest,full

" use indents of 2 spaces, and have them copied down lines:
set shiftwidth=4
set shiftround
set expandtab
set autoindent

" have <Tab> (and <Shift>+<Tab> where it works) change the level of
" indentation:
inoremap <Tab> <C-T>
inoremap <S-Tab> <C-D>
