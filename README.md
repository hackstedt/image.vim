# image.vim
View images in Vim, because Vim is awesome!

![](https://github.com/ashisha/image.vim/blob/master/screenshot/image.vim.jpg)



Features
=========
* Let's you open (preview) images in Vim!
* It's safe, never modifies the original image (unless you force write)


Requirements
============
* Vim with *python3* support. You can verify if your Vim is compiled with python3 using:
  
  `vim --version | grep python3`

  If you see `+python3`, your Vim has python3 support. If not, figure out how to get one.

* Also needs the Python3 library PIL. You can install PIL using `pip install Pillow`

Installation
============
* [Pathogen](https://github.com/tpope/vim-pathogen)
  *  `git clone https://github.com/hackstedt/image.vim ~/.vim/bundle/image.vim`
* [Vundle](https://github.com/gmarik/vundle)
  * `Plugin 'hackstedt/image.vim'`
* [NeoBundle](https://github.com/Shougo/neobundle.vim)
  * `NeoBundle 'hackstedt/image.vim'`
* Manual
  * Copy image.vim into your `~/.vim/plugin/` directory

Thank you!
