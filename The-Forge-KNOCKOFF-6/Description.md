# The Forge Knockoff

https://youtu.be/B567ELEtQX0

For the purposes of the video demonstration, I gave my player infinite money and the first rock mined had only 20 health as opposed to the standard of 100 health.

Game link:

https://www.roblox.com/games/109627297745876/MINEN

## Overview

A low detail mining game.

The player spawns in and gets assigned to the first open plot (similar to Grow A Garden). The player also spawns with a pickaxe which they can use to mine rocks for different ores that go to their inventory (Stone, Copper, Silver, Gold, Diamond-- all with different rarities and drop chances based on player luck stat). The player can also use the anvil at their designated plot to upgrade their pickaxe (only luck and mining power stats have implemented functionality as of now).

## What was used
Indexing for assigning players to plots and assuring that the player can only access the anvil of their plot.

GUI Creation and scaling (it's not all shown in the video but the player is able to click into each of the ores)

Inventory management scripts-- updating player inventory accordingly

Utilizing Datastore for the player's pickaxe stats

Luck influenced RNG system for ore drops

Simple hitboxes for the pickaxe tool

Central ore respawning script for all ores on the map
