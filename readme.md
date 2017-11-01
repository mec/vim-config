# Vim config
Trying to use Vim more so here is my portable config.

## Installation:

    git clone https://github.com/mec/vim-config.git

## Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc

## Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

## Add fonts
You need a font that is patched with symbols so Airline looks right. Nerd Fonts has loads include SIL ones, they use different names to not conflict with the 'standard' versions. Currently using:

- Meslo = Menlo

## Add new modules
I'm usign Pathogen so just clone the repo into the bundle directory:

```git submodule add <repo> bundle/<repo-name>```
