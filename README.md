myLaptop
======

This is a myLaptop - an setup script with inspiration taken from laptop by the folks at Thoughbot.

This contains a bash script that will do the following:

* Installs oh-my-zsh
* Installs homebrew
* Installs git, vim, tmux, node, rbenv and other miscellaneous packages through brew
* Installs the latest version of Ruby through rbenv
* Installs bundler and configures it to use all CPU cores
* Installs Google Chrome, iterm2, atom, the unarchiver and flux through brew-cask
* Installs Powerline Font packages
* Installs various linters for html5, css, js, puppet, elixir and ruby.

Finally it moves over my .vimrc, tmux.conf and zshrc, as well as git template files.

Requirements
------------

* OS X El Capitan (10.11)

Install
-------

$ sudo chown mac
$ ./mac
