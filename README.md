# tmux-bindings-vim

A simple, opinionated set of vim-style keybindings for tmux to get you started. If you're a vim user tired of the default tmux bindings, drop this in and feel right at home.

## 🔗 Interactive Reference

Browse all bindings in your browser: **[keybinding reference](https://p-dealwis.github.io/tmux-bindings-vim/bindings.html)**

## Files

- **`bindings.html`** — Interactive, searchable keybinding reference
- **`~/.tmux.conf`** — The tmux config these bindings are derived from

## Quick Start

```bash
# Back up your existing config
cp ~/.tmux.conf ~/.tmux.conf.bak

# Clone and link
git clone https://github.com/p-dealwis/tmux-bindings-vim.git ~/.tmux
ln -sf ~/.tmux/tmux.conf ~/.tmux.conf

# Reload tmux
tmux source-file ~/.tmux.conf
```

## Prefix Key

The prefix is **`Ctrl + a`** (instead of the default `Ctrl + b`).

## Highlights

| Binding | Action |
|---------|--------|
| `h` / `j` / `k` / `l` | Pane navigation (vim-style) |
| `Alt+h` / `Alt+l` | Previous / Next window |
| `v` / `s` | Vertical / Horizontal split |
| `Ctrl+h/j/k/l` | Resize panes (5 units) |
| `Shift+h/j/k/l` | Resize panes (1 unit) |
| `Ctrl+n` | New window |
| `r` | Rename window |
| `S` | Rename session |
| `/` | Enter copy-mode + search |
| `Y` | Toggle synchronize-panes |
| `q` | Kill server |

## Requirements

- tmux 3.5+
