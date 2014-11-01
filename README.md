dotfiles
========

Here is a simple set of configuration files for OSX.

Requirements
--------

vim, fish, git, ag, tmux

OSX install
--------

    # Install dependencies
    brew install vim fish git the_silver_searcher tmux

    # Setup fish
    sudo 'echo /usr/local/bin/fish >> /etc/shells'
    chsh -s /usr/local/bin/fish
    
    # Install the dotfiles
    mkdir -p ~/local/src
    cd ~/local/src
    git clone git@github.com/Nthalk/dotfiles
    cd dotfiles
    sh install.sh

