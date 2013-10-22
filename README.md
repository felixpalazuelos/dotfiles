Felix Palazuelos dotfiles
================================

This repo includes all my configuration files for Linux distros (i actually use Archlinux). If you want use them, you should clone to `~/dotfiles` and create symlinks to your home directory.


Installation
--------------------------------

An example installation (delete all scripts you will override!)

    git clone git://github.com/felixpalazuelos/dotfiles ~/dotfiles
    rm -r .vim .vimrc .screenrc .gitconfig
    ln -s .dotfiles/vim .vim
    ln -s .dotfiles/vimrc .vimrc
    ln -s .dotfiles/screenrc .screenrc
    ln -s .dotfiles/gitconfig .gitconfig
