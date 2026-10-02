# dotfiles

```
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣶⣶⣾⣿⣻⣿⣿⣿⣿⣿⣿⣶⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⣿⣿⣋⡛⣿⠛⢿⣿⣿⣿⣿⣿⠿⢿⣿⣷⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⣰⠿⢿⠏⠀⠀⠉⡛⠟⠀⣺⣿⣿⣿⣿⣧⡈⢀⣹⣿⣿⢙⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⡀⠘⠉⠀⠁⢀⣀⡀⠀⡠⠀⣴⠛⠉⠀⠀⠉⣹⣿⣿⣿⣿⣿⣦⠃⠀⠀⠀⠀⠀⠀"Where's my fish?"⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣾⣿⣿⣏⣤⣾⣿⣿⣶⣶⣤⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠛⠉⢀⣉⠙⠻⣿⣿⣿⣿⣿⠒⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢻⣿⣿⢿⣿⣿⣏⠙⠉⠉⣴⣾⣿⣧⣿⣿⣿⣾⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠚⣳⢋⠜⠻⠛⠃⠀⠘⠋⠉⠉⠉⠀⠈⠛⠛⣿⣿⣿⣿⠦⡀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣾⣿⠋⡰⠠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⢸⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣻⣯⣴⣡⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⣸⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⣷⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢘⣿⣿⣿⣿⣿⣿⣿⣄⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⣼⣿⣿⣿⣿⣿⣿⣿⣿⣆⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢈⠀⠀⠀⠀⠂⠀⠀⠀⠀⠀⢠⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠱⢌⡑⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠁⢋⠓⠻⣟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡅⠀⠀
```

chezmoi-managed dotfiles for my machines.

## Quick start

```bash
curl -fsSL https://get.chezmoi.io | sh
chezmoi init --apply griimbot/dotfiles
```

## Structure

- `dot_bashrc.d/` — modular bashrc scripts
- `dot_config/` — app configs (nvim, opencode, wezterm, starship)
- `run_once_before_*.sh.tmpl` — bootstrap scripts (run once)
- `run_once_after_*.sh.tmpl` — post-bootstrap scripts (run once)
- `run_onchange_before_*.sh.tmpl` — run on change scripts

## Machines

- **egghead** — NUC, Ubuntu 26.04, Tailscale
