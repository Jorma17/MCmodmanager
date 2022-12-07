MCmodmanager is a simple shell script for Linux systems that aims to make managing mods easier. This script allows you to have mods sorted by category in a directory.
For example, you could have a directory called ```~/Documents/mods``` containing the following directories:
- ```Performance```
- ```Features```
- ```Utility```

Upon executing the shell script, all the mods in those sub-directories will be copied to the mod folder of your choise
while removing the old ones (soft linking doesn't work, I've tried)

Requirements for this to work:
- a mod loader for Minecraft
- a Linux system

If you use a launcher which allows for multiple ```.minecraft``` directories (e.g. MultiMC), you probably want to have this separately for each of them.

This project is a piece of free software licensed under the GPLv3 license. You can modify this and distribute your modified versions as long as you
also make the modified source code publicly available.
