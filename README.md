# My dotfiles

This directory contains the dotfiles for my system

## Requirements
Ensure you have the following installed on your system

### For Ubuntu: install zsh
```bash
sudo apt install zsh
chsh -s $(which zsh)
```

### Homebrew

Install Homebrew and adding Homebrew to current shell session
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Github

```bash
brew install git
```

### Stow

```bash
brew install stow
```

### Oh My Posh

Macos
```bash
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

Ubuntu
```bash
curl -s https://ohmyposh.dev/install.sh | bash -s
```

### Fzf
```bash
brew install fzf
```

### Zoxide
```bash
brew install zoxide
```

### Tmux (Optional)
```bash
brew install tmux

git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Kitty (Optional)
```bash
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin
```

## Installation

After clone, using stow to symlink the dotfiles to your home directory

```bash
cd ~/dotfiles
stow .
```

Install fonts for oh-my-posh

```bash
oh-my-posh font install
```

Load Tmux plugins by launching tmux and pressing `Ctrl Space` + `I` (capital i, as in Install)