## Overview
WSL2 kernel linux-msft-wsl-5.15.167.4 from https://github.com/microsoft/WSL2-Linux-Kernel/releases
Compiled with USB storage, NBD and MMC support

## Instructions
* Extract the kernel image to your home directory (or other preferred location)
* Save .wslconfig in your home directory
* Update the username or path in .wslconfig to match where you put the kernel
* Use `wsl --shutdown` or reboot your system for it to take effect
* Launch your distro and confirm a build date of 2024-11-27 using `uname -a`

## Uninstallation
* Delete .wslconfig
