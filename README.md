# Overview

When opening files in Vim from the shell, this plugin adds an entry to Vim's
command history in the form `:e foo.rb` . Also, when opening files in Vim,
adds an entry to the shell history in the form `vim foo.rb` .

# Installation

This plugin can be installed as a standard Vim package (see `:help packages`).
Simply clone this repository into ~/.vim/pack/plugins/start/vim-history-sync to
install the Vim files for this plugin.

To enable this plugin, add `. /path/to/vim-history-sync/sh/history-sync.zsh`
to your .zshrc. Currently only zsh is supported, although patches are welcome
to add support for other shells.
