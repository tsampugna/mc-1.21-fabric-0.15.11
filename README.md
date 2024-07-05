# mc-1.21-fabric-0.15.11
Fabric Installer and Mods for some Client Side improvements
---
tags:
  - tutorial
  - install
  - minecraft
---


# TLDR;
-  Install Fabric-installer-1.0.1  (See [Installing Fabric](#Installing%20Fabric) below)
-  Launch Minecraft via the Launcher (You should see a new profile to use)
-  Verify the game launches then add all mods to the mods folder (See [Locating Mods Folder](#Locating%20Mods%20Folder) below) 


# Mods
- Better F3 [link](https://www.9minecraft.net/betterf3-mod/)
- Inventory Profiles Next [link](https://modrinth.com/mod/inventory-profiles-next/version/fabric-1.21-2.0.1)
	- Fabric Language Kotlin (required)
	- Fabric API (required)
	- libIPN (required)
	- Mod Menu (optional)
		- Fabric API (required)
		- Text Placeholder API (required)
- JourneyMap [link](http://journeymap.info/)
- Shulker Box Tooltip [link](https://modrinth.com/mod/shulkerboxtooltip)
- Sodium [link](https://modrinth.com/mod/sodium)
The following are Masa Mods and the latest are usually maintained by Sakura before merged into the main branch. Links will go to their repos. Some features of these are not fully working when used as client-side only. 
- MaLiLib [link](https://github.com/sakura-ryoko/malilib/releases)
- Litematica [link](https://github.com/sakura-ryoko/litematica/releases)
- MiniHUD [link](https://github.com/sakura-ryoko/minihud/releases)
- Tweakaroo [link](https://github.com/sakura-ryoko/tweakeroo/releases)
- Item Scroller [link](https://github.com/sakura-ryoko/itemscroller/releases)

> [!warning] Sodium and certain VanillaTweaks Resource Packs may conflict. 
> I'm still testing this out but have not encountered any issues so far:
> 
> From latest.txt under .minecraft/logs:
>```
>The following compatibility issues were found with installed resource packs:
>- Resource pack: RESOURCE_PACK_MC1.21.x.zip
>	- Problem found: 
>		- Description:
>			The resource pack modifies shader include files, which are not fully supported
>		- More information: https://github.com/CaffeineMC/sodium-fabric/wiki/Resource-Packs
>		- Files: 
>		- shaders/include/fog.glsl
>```

# Installing Fabric

More detailed instructions are on the [Fabric Wiki](https://fabricmc.net/wiki/install)
#### Regular installation
##### Mojang's Minecraft Launcher
1) Download the Fabric Installer from the [downloads](https://fabricmc.net/use/) page
2) Open the installer. In the window you can select the Minecraft version, loader version (latest recommended), and the install location (default recommended)
	a) To show snapshots in the Minecraft versions dropdown, tick the 'Show Snapshots' checkbox
	b) The install location is the location of Minecraft Launcher. If you want to change your instance's directory use Minecraft Launcher's instance options
3) Press Install. A new game version and profile will be created in the launcher's menu, which you can now use to launch Fabric
4) You may then want to launch your newly created instance once, and then add [Fabric API](https://modrinth.com/mod/fabric-api/versions) to your instance's mods folder as most mods will need it

![](attachments/Pasted%20image%2020240705134117.png)

![](Pasted%20image%2020240705134159.png)

![](launcher01.png)

![](Pasted%20image%2020240705135715.png)

##### Locating Mods Folder
Under Installations, you can duplicate the Installation and click on the folder to locate your .minecraft folder. Place all Mods in the mods folder.
![](launcher02.png)

