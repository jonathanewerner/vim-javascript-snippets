# vim-javascript-snippets

Some javascript snippets meant for usage with [UltiSnips](https://github.com/SirVer/ultisnips) that are indespensable for me. 

## Usage
If you write semicolons:
`let g:UltiSnipsSnippetDirectories = ["UltiSnips", "UltiSnips/javascript-with-semicolons"]`

If you don't write semicolons:
`let g:UltiSnipsSnippetDirectories = ["UltiSnips", "UltiSnips/javascript-no-semicolons"]`

To specify this per project, get [embear/vim-localvimrc](https://github.com/embear/vim-localvimrc), global gitignore `.lvimrc` files and put a `.lvimrc` file with one of the instructions above into the projects root.
