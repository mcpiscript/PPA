# PPA
Repository for Apt packages. Anything mcpi-related is allowed.

## Current packages
- Planet launcher
- [`python3-morpheus-mcpi`](https://github.com/bigjango13/morpheus-2), a "hack client". Run with terminal using `morpheus`
- [`python3-mcpi`](https://pypi.org/project/mcpi), Minecraft Pi API
- Various dependencies

If you have a cool script, contact us on [Discord](https://dsc.gg/mcpiscript), and we'll add it!

## Installation
```
curl -s --compressed "https://mcpiscript.github.io/PPA/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/mcpiscript.list "https://mcpiscript.github.io/PPA/mcpiscript.list"
sudo apt update
```
## Uninstallation
```
sudo rm -f /etc/apt/sources.list.d/mcpiscript.list
sudo apt update
```
