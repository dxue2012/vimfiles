This vimfiles are cloned from soveran's with a few personal adjustments in snippets and colors.

Usage
=====

First, backup your existing `.vim` directory:

    mv ~/.vim ~/.vim-backup

And backup your configuration files:

    mv ~/.vimrc ~/.vimrc-backup
    mv ~/.gvimrc ~/.gvimrc-backup

Now clone this repository:

    git clone git://github.com/tonchis/vimfiles.git ~/.vim

In your `~/.vimrc` put this:

    source ~/.vim/vimrc.vim

And in your `~/.gvimrc` put this:

    source ~/.vim/gvimrc.vim

Finally, you will need to install `curl`

    sudo aptitude install curl

You may want to explore the `~/.vim/config` directory to see what's
included and `~/.vim/config/mappings.vim` to see how to use the
available tools.
