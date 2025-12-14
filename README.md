# Workspace setup
## Steps for Windows with WSL
1. Install [WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
2. Install [NixOS for WSL](https://github.com/nix-community/NixOS-WSL)
3. Install **FiraCode** fonts from https://www.nerdfonts.com/
4. Open Windows Terminal and set settings from [windows/ternmial/settings.json](https://github.com/sergey-akhalkov/workspace/blob/main/windows/terminal/settings.json)
5. Open NixOS tab in Windows Terminal then run:
6. `nix-shell -p git`
7. `git clone https://github.com/sergey-akhalkov/workspace.git`
8. `sudo nixos-rebuild switch --flake ./workspace/nixos/flake.nix#noilwhite-pc` 
