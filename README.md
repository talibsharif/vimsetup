Installation:

    git clone git://github.com/talibsharif/vimsetup.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

Adding a plugin
    
    cd ~/.vim
    git submodule add <submogile git url> bundle/<pluginname>
    # Example: git submodule add http://github.com/tpope/vim-fugitive.git bundle/fugitive
    git add .
    git commit -m "<Your commit message>"
