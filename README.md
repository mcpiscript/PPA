# PPA
Repository for Apt packages. Anything mcpi-related is allowed.
## Installation
```
curl -s --compressed "https://mcpiscript.github.io/PPA/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/mcpiscript.list "https://mcpiscript.github.io/PPA/mcpiscript.list"
sudo apt update
```
## Uninstallation
```
sudo rm -f /etc/apt/sources.list.d/mcpi-revival.list
sudo apt update
```
