Welcome to the Dusk SDK!!!

• You can load Quake 1, Half-Life and Quake 3 BSP files (including BSP2, not to be confused with Quake 2)
• You cannot make maps for any game mode other than campaign mode at this time.
• Custom model replacements didn't make it into this build, they'll be coming soon! You can still replace textures and sounds.
• Loading texture WADs is not yet supported, so some maps may have missing textures.
• The console is not present in this build. Nor is any form of multiplayer.
• A new cheat has been added: NBCLIP, which will toggle noclip mode.
• There is no func_vehicle yet. I am sorry.
• Water will only work when func_water is used, we don't (yet) support implicit water through texture names.
• Transparent textures in Half-Life BSPs are not yet supported.
• Quake 3 BSP support is rather preliminary, so expect collision to be not quite right.
• Half-Life level transitions are not yet supported.

Workshop support will be coming in a future patch, stay tuned and enjoy!

HOW DO I LOAD MAPS?
Go into the DUSK game folder (SteamApps/common/Dusk) and find the SDK/mnt/local folder.
Inside this folder, create a new folder for your mod (for example: halflife_maps)
Then inside that folder, create a new folder called maps. Put all of your BSPs in here. Once you enable your mod in the modding menu, they will be accessible from Campaign -> Custom Level
Quake-format maps will require palette.lmp inside the mod folder (halflife_maps in the previous example)

HOW DO I MAKE MODS?
Create a folder in SDK/mnt/local and name it whatever you want your mod to show up as in the in-game menu.  Inside that folder, textures/sounds/maps should be placed in corresponding folders named "textures," "sounds," and "maps."  If you want sounds or textures to replace the default ones, name them the same thing as the corresponding sound/texture found in SDK/mnt/local/sounds or SDK/mnt/local/textures (the file extension needs to be the same as well).  Make sure to activate the mod in the modding menu.  See above for more information about loading custom maps.

REFER TO ENTITIES.TXT FOR THE LIST OF ENTITIES DUSK SUPPORTS

Visit Discord.gg/newblood for more information and support