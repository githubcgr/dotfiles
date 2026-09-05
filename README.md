# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Usage on a new machine

1. Make sure you have an SSH key set up for GitHub on the new machine.
2. Clone this repo into place:
   ```bash
   git clone git@github.com:githubcgr/dotfiles ~/.config/nvim
   ```
3. Open `nvim` — plugins install automatically, pinned to the versions in `lazy-lock.json`.

To sync changes back after editing your config:
```bash
cd ~/.config/nvim
git add -A
git commit -m "..."
git push
```
