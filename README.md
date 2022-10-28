# Nvim-starter-pack
Nvim-starter-pack is repo for quick get start use neovim:

- Files can be searched with vim-clap.
- Have a nerdtree managed menu.
- Split terminal for use command.
- Support smart suggest in multiple language.

<img src="https://raw.githubusercontent.com/prtha112/nvim-starter-pack/main/Screenshot%202565-10-28%20at%2002.11.19.png" alt="drawing" style="width:500px;"/>

## Installing Neovim
Homebrew on macOS or Linux
```sh
brew install neovim
```
Pre-built archives
```sh
curl -LO https://github.com/neovim/neovim/releases/download/nightly/nvim-macos.tar.gz
tar xzf nvim-macos.tar.gz
./nvim-macos/bin/nvim
```
## Config foler
```sh
cd ~
mkdir .config
mkdir nvim
touch init.vim
```

## Requirement
1. [Python3](https://docs.python-guide.org/starting/install3/osx/)
2. [Rust](https://www.rust-lang.org/tools/install)
3. [Node](https://nodejs.org/en/download/)
4. ```sh npm install --global yarn ```
5. ```sh arch -arm64 brew install ctags ```

## Install 
```sh
:PlugInstall
```

## Clean Plugin
```sh
:PlugClean
```
