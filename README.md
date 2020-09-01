# GameExec - Linux Game Launcher

## Short description:
With this script you can manage and run Windows games via Proton.
- Can be executed either by running ./GameExec directly from the terminal or by running GameExec.desktop from a file manager.
- Remember to edit the script's path in GameExec.desktop if you plan to move it to a different directory from GameExec.

![GameExec Screenshot](https://github.com/PerseusArkouda/GameExec/blob/master/GameExec-Screenshot.jpg?raw=true)

### How to use:
1) Install Steam client and login.
2) Install zenity.
3) Proton can be installed via GameExec directly.
4) GameExec will create a new GameExec.conf the first time it runs.
5) Add installed games to the game list and launch them.

### Dependecies:
- zenity
- Linux Steam client
- Proton (offers auto install if not found)
- An already installed Windows game (it's possible also to be able to install games or programs).
- wine (Optional required for winetricks)
- winetricks (Optional for installing additional Windows software)

It's using zenity as GUI and it's able to launch, add or remove games.
Modifications are possible by editing GameExec.conf (or creating if not existing).
#####  Example:
 ProtonBottle=/path/to/the/bottle
 ProtonExec=/home/${USER}/.steam/root/compatibilitytools.d/Proton-5.9-GE-5-ST/proton

[Guide to install GPU drivers and Vulkan](https://github.com/lutris/docs/blob/master/InstallingDrivers.md)
