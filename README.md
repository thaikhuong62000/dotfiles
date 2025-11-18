# My dotfiles

This directory contains the dotfiles for my system

## Requirements
Ensure you have the following installed on your system

### Homebrew
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

```bash
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

### Fzf
```bash
brew install fzf
```

### Zoxide
```bash
brew install zoxide
```

### Tmux
```bash
brew install tmux
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
sudo oh-my-posh font install
```

Load Tmux plugins by launching tmux and pressing `Ctrl Space` + `I` (capital i, as in Install)