Felix Palazuelos dotfiles
================================

This repo includes all my configuration files for Linux and SublimeText.


Installation
--------------------------------

An example installation with .bashrc file:

    git clone git://github.com/felixpalazuelos/dotfiles ~/dotfiles
    rm ~/.bashrc
    ln -s ~/dotfiles/bashrc ~/.bashrc

Now with Sublime User folder:

    rm ~/.config/sublime-text-3/Packages/User
    ln -s ~/dotfiles/sublime-text/User ~/.config/sublime-text-3/Packages

For firefox style (change with your profile):

    ln -s ~/dotfiles/firefox/userChrome.css ~/.mozilla/firefox/9shb6xj3.default/chrome/

