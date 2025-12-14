# Workspace Setup

## Prerequirements
Windows with WSL 2.0

## Steps
1. Install https://github.com/nix-community/NixOS-WSL
2. Install **FiraCode** fonts from https://www.nerdfonts.com/
3. Open Windows Terminal and set settings from [windows/ternmial/settings.json](https://github.com/sergey-akhalkov/workspace/blob/main/windows/terminal/settings.json)
4. Open NixOS tab in Windows Terminal then run:
5. `nix-shell -p git`
6. `git clone https://github.com/sergey-akhalkov/workspace.git`
7. `sudo nixos-rebild switch --flake ./workspace/nixos/flake.nix#noilwhite-pc` 
