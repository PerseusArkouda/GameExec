# GameExec - Linux Game Launcher

Short description:
With this script you can manage and run Windows games via Proton.
- Can be executed either by running ./GameExec directly from the terminal or by running GameExec.desktop from a file manager.
- Remember to edit the script's path in GameExec.desktop if you plan to move it to a different directory from GameExec.

How to use:
Install Steam client and login.
Install zenity.
Proton can be installed via GameExec directly.
GameExec will create a new GameExec.conf the first time it runs.
Add installed games to the game list and launch them.

Dependecies:
1) zenity
2) Linux Steam client
3) Proton (offers auto install if not found)
4) An already installed Windows game (it's possible to be able to install a game via Proton).

It's using zenity as GUI and it's able to launch, add or remove games.
Modifications are possible by editing GameExec.conf (or creating if not existing).
 Example:
 ProtonBottle=/path/to/the/bottle
 ProtonExec=/home/user/.steam/root/compatibilitytools.d/Proton-5.9-GE-5-ST/proton
