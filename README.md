# Instantly Better Vim 2013

Damian Conway's vmath plugin for vim as demonstrated at his OSCON 2013
"More Instantly Better Vim" presentation.  Calculates the sum, average,
min, and max for a visual region containing numbers.

# Installation

Recommended using tpope's [pathogen](https://github.com/tpope/vim-pathogen):

```bash
cd ~/.vim/bundle
git clone git://github.com/lionelyoung/vim-instantlybettervim2013
```

# Usage

These commands are available to you:

```vim
"====[ dragvisuals.vim ]===============
vmap  <expr>  <LEFT>   DVB_Drag('left')
vmap  <expr>  <RIGHT>  DVB_Drag('right')
vmap  <expr>  <DOWN>   DVB_Drag('down')
vmap  <expr>  <UP>     DVB_Drag('up')
vmap  <expr>  D        DVB_Duplicate()

"====[ listtrans.vim ]===============
nmap  ;l   :call ListTrans_toggle_format()<CR>
vmap  ;l   :call ListTrans_toggle_format('visual')<CR>
```
# References

 * http://www.youtube.com/watch?v=aHm36-na4-4
