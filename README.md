# monster.vim

Ruby のコード補完プラグイン


## Requirement

* __gem__
 * `gem install rcodetools`


## Screencapture

![monster](https://cloud.githubusercontent.com/assets/214488/3964723/7bc02e7e-278c-11e4-8578-1785aabecf85.gif)

## Using

`<C-x><C-o>` でコード補完を開始します。

## Setting

```vim
" Use neocomplete.vim
let g:neocomplete#sources#omni#input_patterns = {
\   "ruby" : '[^. *\t]\.\w*\|\h\w*::',
\}
```


