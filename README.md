# vim-javascript-snippets

Some javascript snippets meant for usage with [UltiSnips](https://github.com/SirVer/ultisnips) that are indespensable for me. 

## Installation
```viml
" install deps with plugin manager of your choice
Plugin 'SirVer/ultisnips' 
Plugin 'jonathanewerner/vim-javascript-snippets'`

" If you write semicolons:
let g:UltiSnipsSnippetDirectories = ["UltiSnips", "UltiSnips/javascript-with-semicolons"]

" If you don't write semicolons:
let g:UltiSnipsSnippetDirectories = ["UltiSnips", "UltiSnips/javascript-no-semicolons"]
```

To specify the directories per project, get [embear/vim-localvimrc](https://github.com/embear/vim-localvimrc), global gitignore `.lvimrc` files and put a `.lvimrc` file with one of the let instructions above into the projects root.
