# The People's Pack v1.3

This is a bunch of random Minecraft Forge mods for #epic gamers, including Create, IE, Rats, and Tetra.

## Installation

* Download and run [this launcher](https://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.16.5.html); you'll want a client installation.

* This should make a `mods` folder in your `.minecraft` folder (which is usually in `C:\Users\{User}\AppData\Roaming`), but if it doesn't, start up the Minecraft launcher, select the new forge profile, and run the game.
Once it loads, close it, and the `mods` folder should now be present.

* Lastly, you need the mods.
You can either download [the zip in this repo](./peoples-pack-v1.3.zip) (it includes OptiFine `;)`) and unzip the contents into your `mods` folder, or download each of these and throw them individually into your `mods` folder:
  * [AutoOreDictConv](https://media.forgecdn.net/files/3181/99/autooredictconv-1.16.4-16.1.5.jar)
  * [Biomes O Plenty](https://media.forgecdn.net/files/3181/401/BiomesOPlenty-1.16.4-13.0.0.431-universal.jar)
  * [Citadel](https://media.forgecdn.net/files/3131/923/citadel-1.5.3.jar)
  * [Create](https://media.forgecdn.net/files/3167/531/create-mc1.16.3_v0.3e.jar)
  * [Decorative Blocks](https://media.forgecdn.net/files/3166/283/decorative_blocks-1.16.4-1.7.2.jar)
  * [HWYLA](https://media.forgecdn.net/files/3033/593/Hwyla-forge-1.10.11-B78_1.16.2.jar)
  * [Immersive Engineering](https://media.forgecdn.net/files/3189/63/ImmersiveEngineering-1.16.5-4.2.1-131.jar)
  * [InvTweaks](https://media.forgecdn.net/files/3102/237/invtweaks-1.16.4-1.0.1.jar)
  * [JEI](https://media.forgecdn.net/files/3157/864/jei-1.16.4-7.6.1.65.jar)
  * [MDECore](https://media.forgecdn.net/files/3118/780/mdecore-1.16.4-16.1.0.jar)
  * [MGUI](https://media.forgecdn.net/files/3104/239/mgui-1.16.4-3.1.3.jar)
  * [MouseTweaks](https://media.forgecdn.net/files/3035/780/MouseTweaks-2.13-mc1.16.2.jar)
  * [Pam's Crops](https://media.forgecdn.net/files/3076/451/pamhc2crops-1.16.3-1.0.1.jar)
  * [Pam's Food Core](https://media.forgecdn.net/files/3190/867/pamhc2foodcore-1.16.3-1.0.2.jar)
  * [Pam's Food Extended](https://media.forgecdn.net/files/3190/664/pamhc2foodextended-1.16.3-1.0.1.jar)
  * [Pam's Trees](https://media.forgecdn.net/files/3117/43/pamhc2trees-1.16.3-1.0.0.jar)
  * [RandomPatches](https://media.forgecdn.net/files/3182/722/randompatches-2.2.1-forge.jar)
  * [Ratlantis](https://media.forgecdn.net/files/3072/700/ratlantis-1.0.0-1.16.3.jar)
  * [Rats](https://media.forgecdn.net/files/3174/306/rats-7.1.0-1.16.5.jar)
  * [Tetra](https://media.forgecdn.net/files/3187/37/tetra-1.16.4-3.6.0.jar)
  * [Torchmaster](https://media.forgecdn.net/files/3170/451/torchmaster-2.3.6.jar)
  * [Waystones](https://media.forgecdn.net/files/3098/215/Waystones_1.16.3-7.3.1.jar)
  * You can also throw [an OptiFine jar](https://optifine.net/downloads) in there; you don't have to run the installer like you normally do with OptiFine, just throw the installer's jar in `mods` same as the rest

Launch Minecraft, and you should be good to go.

## About

As a disclaimer, this isn't a perfect representation of the modded Minecraft experience.
If you were to use a different, properly maintained pack, like any from [the FTB Team](https://feed-the-beast.com/), you'd have a much cleaner experience.
This is just me throwing together some packs that I think play nicely with each other.

If you're using my server to play this pack, I also have [these datapacks](https://vanillatweaks.net/share#KK8V5D) from [Vanilla Tweaks](https://vanillatweaks.net/picker/datapacks/) installed.
You don't need to install these yourself, since they're all server-side, but I'm leaving there here in case you want to learn more about them:
* Experimental
  * Confetti creepers
* Hermitcraft
  * Wandering trades
* Mobs
  * Villager death messages
  * Double shulker shells
  * Dragon drops
* Items
  * Player head drops
  * Armored elytra
* Survival
  * Villager workstation highlights
  * Multiplayer sleep
  * Graves
  * Custom nether portals
  * Armor statues
  * Unlock all recipes
  * Fast leaf decay
  * Cauldron concrete

## Notes for Server Admins

* I recommend changing IE's configuration to not generate copper, since Create also creates copper, and the two are compatible
  * If you don't do this, you can edit AODC's config file to automatically convert copper of one type to the other to make player's lives easier
* To use Biomes O' Plenty, you need to set the `level-type` in `server.properties` to `biomesoplenty`
