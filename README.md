# Dotfiles

This repo includes a Git submodule for Neovim and the tmux configuration (excluding plugins).

## Clone and initialize submodules

```bash
git clone https://github.com/ngtanthanh-qc/dotfiles.git ~/.config
cd ~/.config
git submodule update --init --recursive
```

## Update submodules later

```bash
git submodule update --remote --merge
```
