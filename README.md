# fiesta maintenance world

This is the FiestaSMP maintenance world save from 2026-11-26. It's a separate world; the main Overworld, Nether and End are in the other repos. This repo doesn't include plugins, server settings or a full server backup.

The world files add up to about 35 MB. Leave some extra space to download and extract it. Use Java Edition and the same Minecraft/Paper version the save came from.

## download

Open [Releases](https://github.com/open-fiestasmp/world-maintaince/releases), choose `snapshot-2026-11-26`, then download **Source code (zip)**. Extract it. The folder with `level.dat` at its top level is the save. `README.md` is just this guide and can be removed after you read it.

## use it in java single-player

1. Close Minecraft.
2. Copy the extracted folder with `level.dat` into your Java Edition `saves` folder. On Windows that's `%appdata%\.minecraft\saves`; on macOS it's `~/Library/Application Support/minecraft/saves`; on Linux it's usually `~/.minecraft/saves`. Custom launchers may use a different game folder.
3. Rename the folder to `Fiesta maintenance` and open it with a matching Minecraft version. Back up first if you already have a save with that name.

## use it on a server

1. Stop the server and back up its current world folders.
2. Extract this archive and put the folder with `level.dat` in the server directory. Name it `maintenance` if that's the name your server or world manager expects.
3. If you want it to be the server's main world, set `level-name=maintenance` in `server.properties` while the server is stopped. If a world manager plugin handles it, use that plugin's import process instead.
4. Start the same Paper/Minecraft version and check the console before anyone joins.

Don't replace `world`, `world_nether` or `world_the_end` with this folder unless you mean to replace those worlds.

## extra files

`.world-tier/access` has small region access-time markers. Minecraft doesn't need them to load the save; keep them if you want that access history.

This FiestaSMP community backup isn't affiliated with Mojang or Microsoft. It doesn't include or grant a Minecraft license.

Backed up and uploaded using Fiesta tools by `gautam652`.
