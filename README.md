## VIM-tips

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

### Version Control
* [vim-gitgutter](https://github.com/airblade/vim-gitgutter) - It shows a git diff in the gutter (sign column) and stages/undoes hunks.
* [vim-fugitive](https://github.com/tpope/vim-fugitive) - Use git command in VIM.

### Stauts/tabline
* [vim-airline](https://github.com/vim-airline/vim-airline) - Lean & mean status/tabline for vim that's light as air

### File Manager
* [nerdtree](https://github.com/scrooloose/nerdtree) - The NERD tree allows you to explore your filesystem and to open files and directories.
* [nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin) - A plugin of NERDTree showing git status

### File Searcher
* [ctrlp](https://github.com/ctrlpvim/ctrlp.vim) - Full path fuzzy file, buffer, mru, tag, ... finder for Vim.
* [ack.vim](https://github.com/mileszs/ack.vim) - keywords search tool from Vim, with an enhanced results list

### Navigation
* [vim-easymotion](https://github.com/easymotion/vim-easymotion) - EasyMotion provides a much simpler way to use some motions in vim.

### Programming
* Tag display
    * [tagbar](https://github.com/majutsushi/tagbar) - A class outline viewer for Vim.
* Comment out lines
    * [nerdcommentor](https://github.com/scrooloose/nerdcommenter) - powerful and easy to use comment tools
    * [tComment](https://github.com/vim-scripts/tComment) - TComment works like a toggle, i.e., it will comment out text that contains uncommented lines, and it will uncomment already commented text.
* Code Snipes
    * [delimitMate](https://github.com/Raimondi/delimitMate) - provides insert mode auto-completion for quotes, parens, brackets, etc.
    * [snipMate](https://github.com/garbas/vim-snipmate) - SnipMate aims to provide support for textual snippets, similar to TextMate or other Vim plugins like UltiSnips.
* Indention
    * [indentline](https://github.com/Yggdroot/indentLine) - A vim plugin to display the indention levels with thin vertical lines
* Line Number Toggling
    * [togglenumber](https://github.com/vim-scripts/togglenumber) - Easy toggle between different numbering modes
* Error Checking
    * [syntastic](https://github.com/scrooloose/syntastic) - Syntax checking hacks for vim

##### Python
* Completion
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) - Awesome Python autocompletion with VIM
* Autoformat
    * [flake8-vim](https://github.com/andviro/flake8-vim) - Frosted, pep8 and mcabe checker for Vim
* Useful VIM scripts

    ```
    # Number of spaces that a <Tab> in the file counts for.
    set tabstop=4
    # Number of spaces to use for each step of (auto)indent.  Used for |'cindent'|, |>>|, |<<|, etc.
    set shiftwidth=4
    # Converting tabs to spaces.
    set expandtab
    # Remove tailing spaces upon saving the file
    autocmd BufWritePre * :%s/\s\+$//e
    ```
    
##### Go
* Completion/Autoformat/Error Checking:
    * [vim-go](https://github.com/fatih/vim-go) - Go (golang) support for Vim, which comes with pre-defined sensible settings (like auto gofmt on save), with autocomplete, snippet support, improved syntax highlighting, go toolchain commands, and more. 
    
##### javascript
* Syntax Checking:
    * [es.next.syntax.vim](https://github.com/othree/es.next.syntax.vim) - This syntax file is for ES7 and future syntax
    * [vim-jsx](https://github.com/mxw/vim-jsx) - Syntax highlighting and indenting for JSX
* Completion
    * [vim-nodejs-complete](https://github.com/myhere/vim-nodejs-complete) - Node.js `omnifunc` function of vim
