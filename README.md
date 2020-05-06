# Basic Dusk SDK Framework 

This is a basic folder structure and asset framework for Dusk given the current decentralised nature of gathering additional required SDK assets and tools 

## This repo begins in your Dusk SDK folder

### dusk_wads_tb.7z - unzip these wads for TrenchBroom.
+ **dusk.wad** - general textures

+ **dusk_transparent.wad** - transparent textures

### dusk_wads_tb.7z - unzip the wad for J.A.C.K. (WAD3 format not compatible with TrenchBroom)
+ **dusk_wad3.wad** - general/transparent textures

**dusk.fgd** - entity definitions for the TrenchBroom editor 

**dusk_qmdl.fgd** - entity definitions for the J.A.C.K. editor 

**entities.txt** - list of entities both sharing with and similar to Half-Life & Quake

**quake.pal** - original Quake palette for J.A.C.K. configuration 


## Other essential tools

### Level Creation

 - [TrenchBroom](https://github.com/kduske/TrenchBroom/releases) - Level editor supporting Quake engine games including Half-Life. Windows/Mac/Linux. Dusk recommended.

 - [J.A.C.K.](https://jack.hlfx.ru/en/download.html) - Level editor supporting Quake engine games *especially* Half-Life, given its on par in general function with Valve's Hammer Editor. Windows/Linux. 
	* Generally any program capable of spitting out Quake engine based/related .bsp files can work as your level editor for Dusk. Essentially anything on [this](https://quakewiki.org/wiki/Mapping_tools#Level_Editors) list should work. Direct support (and especially entity recognition) is on you thus far for most alternative editors.
 
 - [ericw-tools](https://github.com/ericwa/ericw-tools/releases) - Needed to compile your .map files into playable .bsp levels. Dusk recommended.
	* Assuming, based on your needs or experimentation, other qbsp based compiler variations should compile your level just fine for Dusk to load. Visually, YMMV using the many different compile sets available across the idtech family depending on its original intended game or engine version.

 - [MakeWad](https://github.com/NewBloodInteractive/MakeWad/releases) - Nifty WAD maker deriving from a simple group of PNGs. Dusk recommended.
	* Since older Quake engine levels generally load their WADs just fine with Dusk, other WAD2 compatible tools should output readable WADs for Dusk levels.

