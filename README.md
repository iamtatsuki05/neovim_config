# How to set up
```sh
# terminal
brew install neovim
brew install bat
brew install ripgrep
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

git clone https://github.com/tomasiser/vim-code-dark.git ~/.config/nvim/bundle/vim-code-dark.git
ln -s ~/.config/nvim/bundle/vim-code-dark.git/colors/codedark.vim ~/.config/nvim/colors/codedark.vim

# neovim
:PlugInstall

# optional
## terminal
git clone https://github.com/github/copilot.vim \
   ~/.config/nvim/pack/github/start/copilot.vim
## neovim
:Copilot setup
```
