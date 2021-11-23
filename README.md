# EfficientNohits

Enables the configuration of various things in game that make nohitting go a little more smoothly
Also adds automatic max HP and mana items
Works in multiplayer (probably)

Note that if you're using Calamity's Armaggedon, you'll have to set despawn things to "On Hit" rather than "On Death," as the death hook is not fired when killed by Armaggedon.

Currently supported features:
- You can choose to despawn bosses, hostile NPCs (not including bosses), friendly NPCs, hostile projectiles, friendly projectiles, and dusts on death or on hit
- Allows the disabling of rain, events/invasions, and fallen stars
- You can choose to automatically destroy pickup hearts, mana stars, coins, and all other grounded items
- Players can override their respawn HP
- Players can clear the in game chat automatically on respawn, with a configurable delay
- Players can immdeiately stop boss music on respawn
- Players can reset the in game lighting on respawn
- Allows the display of fight stats in chat (attempt number, boss health at the end of the attempt, and slowdown percentage) on respawn
- Allows the ability to display the session attempt number above the player's head, also with a configurable timer
- Adds the Max Life Crystal, Max Life Fruit, and Max Mana Crystal, which each automatically use the max number of their respective bases
