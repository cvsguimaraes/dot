# Refs Index

## Purpose
The `/code/blss/meta/refs` directory is the old dotfiles reference tree. It is not active config; it is a historical source we will slowly filter and merge into the new structure.

## How To Use
- Treat this directory as read-only reference material unless explicitly told otherwise.
- When creating new modules, scripts, or configs, check here for past conventions and reuse the ones that still fit.
- If you need to pull something forward, copy into the active tree and adapt it; do not edit in place.

## Important Notes
- Some config directories are still symlink-hooked (vscode, keyd, etc). Handle changes carefully and confirm where symlinks point before editing.

## Directory Map
- `bin/` — legacy scripts and entrypoints.
- `cfg/` — legacy application configs.
- `dot/` — legacy dotfiles layout.
- `run/` — legacy runtime state references.
- `src/` — legacy modules and shared logic.
