# Dotfiles

This is my ZSH configuration and personal dotfiles. Please review everything before you attempt to use them.
Some things might be OS X specific, but I try to keep everything as platform-agnostic as possible.
This is a public repository mostly for easy installs on additional machines, but feel free to take a look!

# Installation

1. Clone this repository in ~/.dotfiles, **with submodules**:

        git clone --recursive [this_repos_url] ~/.dotfiles

2. Run `./install` once (creates dotfile symlinks and such)

3. Open a new shell

# Important Files

- **install** : Installs everything on a new machine (mostly creating symlinks and reloading the shell)
- **bootstrap.zsh** : The entry point for ZSH shell bootstrapping (sourced in .zshrc)

# Directories

- **dotbot** : Contains dotbot (dotfile symlink manager) and its configuration
- **dotfiles** : Contains dotfiles that are symlinked by dotbot in $HOME
- **scripts** : Contains small scripts that are made available on the $PATH
- **shell** : Contains shell configuration files (commands, key bindings and more)
- **zgen** : The zgen submodule
