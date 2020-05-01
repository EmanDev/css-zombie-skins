# Counter-Strike: Source Zombie Skins
A compilation of configured zombie skins for zombie riot of Counter-Strike: Source. This is to replace default zombie skin settings but instead of replacing everything, some skins that are corrupted have been removed, some skins are added, and some remained as is.

## Skins Included

1. [CF Mutant/Hulk Zombie (Big and Small Version)](https://gamebanana.com/skins/download/135208)
2. [HL2 Zombie Package](https://gamebanana.com/skins/114533)
3. [Yeti](https://gamebanana.com/skins/137296)
4. [S-Low Zombie Boss Package](https://www.moddb.com/mods/zombie-riot/downloads/boss-pack)
   1. Berserk
   2. Centurion
   3. Hunter
   4. Krall
   5. Spawn
   6. Theron Guard
   7. Titan

## Updates and Releases

No **UPDATES** and **RELEASES** yet. Always check this section before downloading the files here.

## Request

If you want me to add more skins feel free to make an [Issue](https://github.com/EmanDev/css-zombie-skins/issues) and be sure to add the following info.

1. Skin Name
2. Skin Link

## Installation and Usage

Installation: Extract the files to your server folder > cstrike folder

Default Usage: 

1. Copy the contents from downloads.txt then paste it to cstrike/addons/sourcemod/configs/downloads.txt
2. Copy the contents from models.txt then paste it to cstrike/addons/sourcemod/configs/models.txt
3. Configure zombies.txt in cstrike/addons/sourcemod/configs/zombies.txt using the following format below (Code A). Put it inside the wrapper (Code B). But always give proper indention and spacing to sort it out properly if you are planning to add more skins.

```
// Code A - Follow Default Value!

"zombie4"
	{
		"type"		"normal"
		"model"		"models/player/Cf_TitanHulk/titanhulk.mdl"
		"health"	"100"
		"speed"		"360"
		"gravity"	"0.9"
		"jump"		"17.0"
		"fov"		"110"
	}
```

```
// Code B

"zombies"
	{

​		// You can put Code A here

​		// Default Skin

​		// You can put Code A here

​		// Default Skin

​		// You can put Code A here

​	}
```

## Customization

This part is an advanced usage to be precise and you should be good enough to configure some skins here.

1. Basically put the contents of downloads.txt to downloads.txt
2. Basically put the contents of models.txt to models.txt
3. Configure added zombie skins in zombies.txt
4. **Customization Part:** This is quite simple, I'm just gonna tell you to just include/exclude skins you want and install them manually.

## Requirements

1. Counter-Strike: Source
2. Counter-Strike: Source Dedicated Server (SRCDS)
3. Installed Zombie Riot Mod or Zombie Mod on the Server

