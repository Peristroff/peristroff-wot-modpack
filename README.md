# What
This is my modpack for World of Tanks, a couple of mods that I use to make the game more enjoyable, but sometimes the mods won't be updated, which in that case i'll leave the link to Plazmakeks or Wargaming mod portal, since they updates the mods more often.

Mod list:
- [Distance Marker](https://wgmods.net/6662/)
- [Battle Hits](https://wgmods.net/5912/)
- [Auto Claim Tour of Duty Missions](https://pkmods.com/auto-claim-tour-of-duty-missions-by-anne_domini/)
- [~~Server Reticle~~](https://pkmods.com/awfultanker-server-reticle/) (Deprecated on version 1.26.1.1)

# Ok, but why
I wanted to use my knowledge in git to create this modpack, and also to make it easier to install the mods, since you can just clone the repository and that's it.

# How to use
## Prerequisites
- [Git bash](https://git-scm.com/downloads)

## Installation
- Go to your World of Tanks folder, usually located at `C:\Games\World_of_Tanks_NA`
-  Right click on the folder and select `Git Bash Here`
- Run the following commands:
```
git init
git remote add origin https://github.com/Peristroff/peristroff-wot-modpack
git fetch origin
git merge origin/main --allow-unrelated-histories
git branch --set-upstream-to=origin/main master
```
- Done! Now you have the mods installed.
- If the game has been updated and you want to update the mods, just run the following command:
```git pull```
- If the mods doesn't work, just delete the mods since they may not be updated for the current version of the game.