# This is a reposity for all my dot files
## for vim
```
apt install vim
echo "source ~/projects/opensource/dotfiles/vim/vim-init/vim.init" > ~/.vimrc

:PlugInstall
```
need to install ycmd

## for zsh
```
apt install zsh
chsh -s /bin/zsh

# for oh-my-zsh
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh

# for dotfile
echo "source ~/projects/opensource/dotfiles/zsh/.zshrc" > ~/.zshrc

# for extentions
apt install autojump
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# then refresh these config
zsh
```

## for tmux
```
apt install tmux
echo "source ~/projects/opensource/dotfiles/tmux/.tmux.conf" > ~/.tmux.conf
```
