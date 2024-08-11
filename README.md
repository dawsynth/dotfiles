# dawsynth's dotfiles

Requirements:
- `zsh >= 5.9`
- `tmux >= 3.4`
- `neovim >= 0.10.0`
- `alacritty >= 0.13.2`



Install:
```
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
git clone --bare git@github.com:dawsynth/dotfiles.git $HOME/.dotfiles
dotfiles config --local status.showUntrackedFiles no
dotfiles checkout
```
