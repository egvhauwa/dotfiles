# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
sudo apt install git
```

### Stow

```
sudo apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
git clone git@github.com:egvhauwa/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .
```

## Zsh

Install using Oh My Zsh (https://github.com/ohmyzsh/ohmyzsh)

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### powerlevel10k

Powerlevel10k is a theme for Zsh (https://github.com/romkatv/powerlevel10k). Install via Oh My Zsh

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
