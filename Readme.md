
## Installation

*vim-sublime* includes [Vundle](https://github.com/VundleVim/Vundle.vim) package manager and some external plugins.

Install Vundle

`$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

Install *vim-sublime* `.vimrc`

`$ curl https://raw.githubusercontent.com/grigio/vim-sublime/master/vimrc > $HOME/.vimrc`

Then open `vim` and run

`:PluginInstall`

Add the plugin colors

`$ cd`

`$ git clone https://github.com/flazz/vim-colorschemes`

`$  mv vim-colorschemes/colors/ .vim`

`$ rm -rf vim-colorschemes`

Quit and enter in `vim` again to apply the changes

You can also add machine specific config to `~/.local.vim`

For best results make sure your $TERM env variable is 256 colours; `export TERM=xterm-256color`

**Note**: to have the correct font in the bottom bar you need a [Powerline](https://github.com/Lokaltog/powerline-fonts) font installed and selected in the terminal.
