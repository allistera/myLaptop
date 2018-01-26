myLaptop
======

This is a myLaptop - an setup script with inspiration taken from laptop by the folks at Thoughbot.

This contains a bash script that will do the following:

* Installs oh-my-zsh
* Installs homebrew
* Installs git, vim, tmux and other miscellaneous packages through brew
* Installs Powerline Font packages

Finally it moves over my .vimrc, tmux.conf and zshrc, as well as git template files.

Install Mac
-------

$ sudo chown mac
$ ./mac

Install Linux
-------

Note you must have the following packages installed:

* Git
* Vim
* Tmux 
* Lnav
* Peco

$ sudo chown linux
$ ./linux
