# requires

vim >7.4 and >8.0 better or neovim

# install

1. copy vimrc to /root/.vimrc

2. install vim plug manage "plug"

* for vim
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

* for neovim
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

3. install plugs

vim .vimrc

run ":PlugInstall"
