# Pixelmon-Allow-Vanilla-Spawns
A Minecraft datapack for the Pixelmon Reforged Mod (1.16.5) that allows for vanilla spawns. This was made for the Pixelmon beta 9.0.9+, any other versions are untested.
After the 9.0.9 Pixelmon update they changed the way that Pixelmon spawn, allowing datapacks to change spawning. This ended up breaking the default behavior of the `allow-vanilla-mobs` property in their config, replacing vanilla mobs with Pixelmon. This datapack is made to fix that issue, allowing you to continue to have the previous behavior of the mod from version 9.0.8 and before.

## Before Installing
To install this datapack you need to open your world, you can either disable the `allow-vanilla-mobs` property in your Pixelmon config, or once you apply kill all pixelmon to remove all of the extra spawned pixelmon by doing the command `/kill @e[type=pixelmon:pixelmon]`

## How To Install
1. Open your world file (normally located `%appdata%/.minecraft/saves/<WORLD_NAME>`
2. Open the `datapacks` folder
3. Put the folder `pixelmon-allow-vanilla-spawns` into the `datapacks` folder (It needs to be inside the pixelmon-allow-vanilla-spawns folder, do not extract the directory should be `%appdata%/.minecraft/saves/<WORLD_NAME>/datapacks/pixelmon-allow-vanilla-spawns`
4. Open the world and type `/datapack enable "file/pixelmon-allow-vanilla-spawns"`
5. Wait for the game to reload completely and it should be applied
