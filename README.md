# dotfiles-rofi

Config for [rofi](https://github.com/davatorium/rofi) (application launcher / menu), theme-integrated via the `theme` submodule — includes the theme picker (`theme-menu.sh`, bound to SUPER+CTRL+SPACE).

Part of the [dotfiles-arch](https://github.com/SaratAngajalaoffl/dotfiles-arch) multi-repo dotfiles system.

## Layout

- `config` → `~/.config/rofi` (see `.links`)
- `config/colors.rasi` is gitignored — it's a symlink to the active theme's colors, not tracked content (see the `theme` submodule)

## Setup

Not used standalone — applied by the parent repo's `install.sh`, which reads `.links` and symlinks `config` into place.
