# tmux-bindings

Vim-style tmux configuration and an interactive HTML keybinding reference.

## Files

- **`bindings.html`** — Interactive, searchable keybinding reference (open in a browser)
- **`~/.tmux.conf`** — The tmux config these bindings are derived from

## Quick Start

```bash
# Copy the config
cp ~/.tmux.conf ~/.tmux.conf.bak
ln -sf ~/.tmux/tmux.conf ~/.tmux.conf

# Reload tmux
tmux source-file ~/.tmux.conf

# View bindings reference
open ~/.tmux/bindings.html
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
