# CLAUDE.md — surfn-orange

## Project overview

Standalone repo for the **Surfn-Orange** icon theme, split out of the `erikdubois/surfn`
monolith. See [README.md](./README.md).

## Current state

Ships one theme: `usr/share/icons/Surfn-Orange/`. Packaged as `surfn-orange-icons-git` (recipe in
`~/KIRO-PKG-BUILD-ICONS/surfn-orange/`), `depends=('surfn-icons-git')` — the base Surfn theme.

## Patterns & decisions

- Theme dir PascalCase; repo/package lowercase. `icon-theme.cache` gitignored (rebuilt by
  the pacman hook on install). Bash scripts follow the canonical Kiro template.
