# qwskins
Skins for the Quake multiplayer community. Because *beautiful skins don't need to compromise visibility*.

New and old skins, for both the new and regular player model.

choose a skin for you or your team! make your own, oh and how about distinguishing enemies during the game? You got it right here.
![Overview screenshot. Most skins are not shown!](https://github.com/mushis/qwskins/blob/master/welcome.png)

# usage
Option 1) Download ***skins.pk3*** and place it on your *quake/qw*. 
Use as your own skin, as a teammate or enemy skin (`/teamskin` or `/enemyskin`). If other players have the skin you're using, they'll see it in the game (as long as they set `/teamskin` or `/enemyskin` to `""` - empty).
To list all the skins you have in the game, type in the console `/fs_dir skins`

Option 2) Download everything. Click on the green button.

Option 3) Download the sets to use in teamgames

Option 4) get a zip here (might not be up to date): https://gfx.quakeworld.nu/details/494/skin-pak-by-link-and-friends/

# contribute
Feel free to create new skins (we recommend using Primevil ones, see  https://gfx.quakeworld.nu/browse/skins/). We encourage you to do it. For your team, your teammate, your neighbour!

Send new skins to mushi (or use git features), they will be uploaded here, and others can get them.

# content
### skins.pk3
all the skins in /SKINS

### /SKINS 
main repository. individual skins are here.

### /sets
sets of skins to be used by yourself or your team

### /fte 
a skin for FTE, allow RGB colors to be given to pants and shirts

### /new Player Model 
skins for the "new player model"

# credits
Credit goes to Link and Mushi, Primevil and all other skins creators
These skins are on https://gfx.quakeworld.nu/ for convenience, but it might not be up to date.

# problem?
Documentation: http://ezquake.sourceforge.net/docs/?player-skins

**Can't see a skin in the game, even though my friend has it set?**
- do you have it on your quake/qw/skins folder? there must be a file there, with the same name as the skin you want to see.

- have you set  `/teamskin` and `/enemyskin` to ""? The value of these commands must be set to empty, or else your client will force the usage of a skin, and you will not see individual skins.

- make sure `/noskins 0` 

- type `/skins`. this will reload skins from your hard drive.

**I want to use the sets for the enemies, but i can't see the different skins!**
- make sure the e1-e4 skin files are on quake/qw/skins and that you have set `/enemyforceskin 3` 
- the equivalent for teammates is are t1-t4 files and  `/teamforceskin 3`

