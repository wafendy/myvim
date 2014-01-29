Vim Setup
===

I use [SMYCK](http://color.smyck.org/ "SMYCK") for all my vim setup.

    mkdir -p ~/.vim/colors 
    cp smyck.vim ~/.vim/colors


Create `.vimrc` with the following lines:

    syntax enable
    set background=dark
    colorscheme smyck



Append the following lines into `.bash_profile`

    export CLICOLOR=1
    export LSCOLORS=GxFxCxDxBxegedabagaced




OSX Terminal Setup
===
Simply go to Terminal->Preferences->Settings->Import, then select Smyck.terminal




