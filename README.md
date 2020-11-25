# Configs files for Linux
A collection of config files, especially dot files.

# Zsh

## Install zsh
`apt install zsh`

## Oh my zsh
```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Use my personal theme: shujun-ys, as configured in .zshrc

## Zsh-autosuggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions.git .zsh-autosuggestions
```

# Tmux
I prefer to use 'C-x' as prefix key

# Emacs
```bash
git clone https://github.com/wsj20369/my_emacs_config.git ~/.emacs.d
```

# Vim
```bash
git clone https://github.com/wsj20369/my_vim_config.git ~/my_vim_config
ln -s ~/my_vim_config/.vimrc .vimrc
```
