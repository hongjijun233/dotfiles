# This is a reposity for all my dot files
## for vim
```
apt install vim
echo "source ~/projects/opensource/dotfiles/vim/vim-init/init.vim" > ~/.vimrc

:PlugInstall

# 需要安装ctags
sudo apt-get install universal-ctags
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

## for enviroment
### for others
```
apt-get install build-essential python3-dev \
 libldap2-dev libsasl2-dev slapd ldap-utils tox \
 lcov valgrind
```
### for go1.20
```
wget -c https://go.dev/dl/go1.20.5.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local
```

### for pyenv
```
curl https://pyenv.run | bash

```
