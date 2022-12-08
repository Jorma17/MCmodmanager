MCmodmanager is a simple shell script for Linux systems that aims to make managing mods easier. This script allows you to have mods sorted by category in a directory.
For example, you could have a directory called ```~/Documents/mods``` containing the following sub-directories:
- ```./Performance```
- ```./Features```
- ```./Utility```

The mods would be then put inside these sub-directories (in this case, `Performance`, `Features` and `Utility`. You can have as many or as little categories as you want, as long as you only put them on the sub-directories and don't put anything else there or in the `./Documents/mods` directory.

Upon executing the shell script, all the mods in those sub-directories will be copied to the mod folder of your choise
while removing the old ones (soft linking doesn't work, I've tried)

**BACK UP YOUR MODS BEFORE USING THIS**


Requirements for this to work:
- a mod loader for Minecraft
- a Linux system with the Bash shell

**INSTALLATION**

If you use a launcher which allows for multiple ```.minecraft``` directories (e.g. MultiMC), you probably want to have this separately for each of them.
Download the script for your launcher of choise (Prism Launcher is recommended) here: https://github.com/Jorma17/MCmodmanager/releases

Then move the shell script somewhere like your ```Documents``` directory:
- ```cd ~/Downloads```
- ```mv ./[shell script name].sh ../Documents/```
- ```chmod +x ../Documents/[shell script name].sh```

This project is a piece of free software licensed under the GPLv3 license. You can modify this and distribute your modified versions as long as you
also make the modified source code publicly available.

If you have any questions/suggestions, feel free to open an issue and I'll try my best to respond.
