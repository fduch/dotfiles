Inspired by 
 - https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49
 - https://github.com/chimurai/dotfiles


# github.com/chimurai/dotfiles

dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

## Prerequisite: Installation of homebrew and chezmoi

This'll install Homebrew and chezmoi.

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/fduch/dotfiles/master/install.sh)"
```

You can also install them manually

## Initialization

Prerequisite: Homebrew & chezmoi

```shell
# Setup
chezmoi init https://github.com/fduch/dotfiles.git

# Configure ~/.config/chezmoi/chezmoi.toml
chezmoi init
```
