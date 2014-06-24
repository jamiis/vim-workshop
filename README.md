# Welcome to Vimsanity!
I hope y'all are ready to "Edit Text at the Speed of Thought"!

![Yay Learning Curve!](http://www.thejach.com/imgs/vim_learning.jpg)

Don't stress, the above is BS! You can be a level 5 vimdroid in a week of regular use. You'll never go back to normal editing; it'll _pain_ you to go back!

## Setup (Mac):
If you are on a Windows junker download [cygwin](https://www.cygwin.com/install.html) because Unix steeze is awesome and I won't be able to help you if you get stuck in Windows' Powershit. And make sure vim is working.

### Swap Esc and Caps Lock
Download [PCKeyboardHack](https://pqrs.org/macosx/keyremap4macbook/seil.html.en) (apparently renamed to Seil?), and _swap_ your Esc and CapsLock keys. You'll thank me later! I use esc far more than CapsLock. CapsLock never should have been invented.

### Download [iTerm 2](http://www.iterm2.com/#/section/home)
Because: duh.

### Vim Config (.vimrc)
I _highly_ recommend installing [my .vimrc](https://github.com/jamiis/dotfiles/blob/master/vimrc) at least for the workshop. You can delete it later.

`$ git clone https://github.com/jamiis/dotfiles ~/your/code/`

If you don't have a ~/.vimrc file:

`$ ln -s ~/your/code/dotfiles/vimrc ~/.vimrc`

Elif you already have a ~/.vimrc file and want to install mine side-by-side. Whoa nelly!

`$ echo "source ~/your/code/dotfiles/vimrc" >> ~/.vimrc`

### Plugins
Plugins allow you to do cool things in vim - duh! There are a handful of vim plugin managers. I use [Vundle](https://github.com/gmarik/Vundle.vim) though Pathogen by the vim demigod [Tim Pope](https://github.com/tpope) is also very popular.

Vundle install is described here but you can most likely get away with running
```
$ mkdir -p ~/.vim/bundle/
$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
```

Install the plugins

`$ vim ~PluginInstall +qall`

If that doesn't work, don't worry we'll get you setup in the workshop.

### Syntax Highlighting
I cannot guarantee this part won't mess up your current terminal coloring scheme. If you don't have a coloring scheme, awesome! Also, I specifically use iTerm2 and have done my .bashrc and .vimrc and iTerm2 coloring scheme around [base16](https://github.com/chriskempson/base16). I recommend doing all -- bashrc, vimrc, iterm2 coloring -- or nothing (or rather _something_ else, because no syntax highlighting in vim will _suck_).

First, install the [base16 iTerm2 coloring schemes](https://github.com/chriskempson/base16-iterm2). I use shapeshifter dark.

`git clone https://github.com/chriskempson/base16-iterm2 ~/your/code/`

[base16 for vim](https://github.com/chriskempson/base16-vim) was already downloaded when we installed the plugins and shapeshifter is the selected colorscheme in my .vimrc so yer all good there!

Talk about (ignore this peoplez):

* vimtutor
* modes (insert, visual, whatever the other ones are called)
* basic movements and combinations of keys
* list some of your most used cmds
* macros
* plugins:
* tpope. Fugitive, NERDTree, CtrlP, Surround
* sublime text, atom
* vim in the command line via .bashrc
* vim chrome extensions. show RES example.
* future of vim: neovim?
