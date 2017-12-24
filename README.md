# vim-laravel
vim for php &amp; laravel vimrc config

操作介紹
Moving around

The above keys help you to move around You can move around when you are in normal mode by typing the following:

h - move cursor left
j - move cursor down
k - move cursor up
l - move cursor right
w - move cursor to the beginning of the next word*
W - move cursor to the beginning of the next WORD*
b - move cursor to the beginning of the previous word*
B - move cursor to the beginning of the previous WORD*
e - move cursor to the end of the next word*
E - move cursor to the end of the next WORD*
ge - move cursor back to the end of the next word*
gE - move cursor back to the end of the next WORD*

Some nice commands

Some commands will act on either a selection or a movement. Movements are the things explained above.

You can change text by selecting a text and typing c or by typing c and choosing a movement.

cw - change word from cursor on
cW - change Word from cursor on
ciw - change inside word
ci" - change inside double quotes
ci{ - change inside { opening and closing brackets  }
ct" - change unttil the double quotes
cf" - change unttil the double quotes, including double quotes

You can delete text by selecting a text and typing d or by typing d and choosing a movement.

dap - delete around paragraph (block of text)
di" - delete inside double quotes
da" - delete around double quotes

There is probably much more, that I either dont remember or did not learn yet.

gf - ggo to file
<ctrl>i - ggo to file
<ctrl>] - ggo to definition (jumps to method definition, use ctags)

Autocomplete

<ctrl>x <ctrl>[completion type]

Where:

f - file completion (from the filesystem)
o - omni completion
n - keyword inside open buffer
k - dictionary completion
l - line completion

When the list opens, use <ctrl>n to next and <ctrl>p for previous

EDIT: Please refer to this post for more details on autocomplete.
The dot command

With the dot command you can repeat the last action
Visual Mode

V - line wise selection
v - character wise selection
<ctrl>v - block wise selection

VIM PHP IDE Plugins

vim-commaobject
vim-sparkup
html5.vim
vim-repeat
vim-surround
hardmode
vim-gitgutter
vim-fugitive
ag.vim
ultisnips
vim-snippets
tcomment_vim
vim-easymotion
auto-pairs
gist-vim.git
nerdtree
ctrlp.vim
tabular
syntastic
argumentrewrap
php-getter-setter.vim
vdebug
phpcomplete.vim

Color Schemes

vim-lucius
vim-colors-solarized

Resources:

Video
Blog Post
Some VIM classes

Reference:
http://mjacobus.github.io/2015/04/17/using-vim-as-a-php-ide.html

