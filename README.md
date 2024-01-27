# My NeoVim config

My NeoVim config for easy deployment.

Originally based on https://github.com/nvim-lua/kickstart.nvim

### Installation

Requirements:
* NeoVim version >= 0.9
* C & C++ Compiler, e.g. gcc, clang.
* Git
* ripgrep

Soft Requirements (for selected LSP servers, see lua/lsp-setup.lua to disable):
* unzip
* golang
* python3

How To:
```sh
mkdir -p ~/.config/nvim
cd ~/.config/nvim
git clone https://github.com/andreasruden/neovim.git .
```

Then launch neovim and let Lazy do its thing:
```sh
nvim
```
