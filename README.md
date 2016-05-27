## VIM-tips

### Version Control
* [vim-gitgutter](https://github.com/airblade/vim-gitgutter) - It shows a git diff in the gutter (sign column) and stages/undoes hunks.
* [vim-fugitive](https://github.com/tpope/vim-fugitive) - Use git command in VIM.

### Stauts/tabline
* [vim-airline](https://github.com/vim-airline/vim-airline)

### File Manager
* [nerdtree](https://github.com/scrooloose/nerdtree)
* [nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin)

### File Searcher
* [ctrlp](https://github.com/kien/ctrlp.vim)

### Navigation
* [vim-easymotion](https://github.com/easymotion/vim-easymotion)

### Programming
* Tag display
  * tagbar
* Comment out lines
  * tComment
* Code Snipes
  * snipMate
* Indention
  * indentline
* Line Number Toggling
  * togglenumber
* Error Checking
    * syntastic

##### Python
* Completion
  * jedi-vim
* Autoformat
  * flake8-vim
* Useful VIM scripts
  * Number of spaces that a <Tab> in the file counts for.
  ```
  set tabstop=4
  ```
  * Number of spaces to use for each step of (auto)indent.  Used for |'cindent'|, |>>|, |<<|, etc.
  ```
    set shiftwidth=4
  ```
  * Converting tabs to spaces.
  ```
  set expandtab
  ```
  * Remove tailing spaces upon saving the file
  ```
  autocmd BufWritePre * :%s/\s\+$//e
  ```
