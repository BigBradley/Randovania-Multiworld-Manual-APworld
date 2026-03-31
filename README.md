# Randovania-Multiworld-Manual-APworld
BigBradley's github repo for the new Archipelago x Randovania implementation.
Some people have asked if Randovania could get an Archipelago implementation, so I thought it'd be extremely funny if I actually made it in some way. Of course, I did this the only way I knew how: Manual APworld. 

Host a RDV Multiworld and join an AP Multiworld with this Manual. This Manual is logically very barren, and is only recommended for Big Asyncs hosted with Archipelago.

DISCLAIMER:
If there are multiple players using this manual in the same AP AND RDV MWs, you should probably figure out how to use Item Plando so your games aren't in each other's worlds, logically hardlocking the AP MW: https://archipelago.gg/tutorial/Archipelago/plando_en 

Requirements:
Latest versions of Archipelago, Randovania, and the Manual Client.

Items:
Every Multiworld compatible game in RDV is now locked behind its own item. Each game can be toggled on or off with a yaml option. You are not allowed to play any RDV game until you receive its item. 

Locations:
- Collect one item from each game. Logically, these checks only require one game to do. If you can't obtain a single item with your starting game, just send the check anyways.
- Collect percentages of the total item count in each game. Logically, these checks require all games. Don't be a stranger to going out of logic. If it is impossible to acquire all items in a game, collect as many as possible and then send the 100% items checks.
- Beat individual RDV games. Logically, these checks require all games. Don't be a stranger to going out of logic.

Goal:
Beat every RDV game you have enabled.

DISCLAIMER:
If there are multiple players using this manual in the same AP AND RDV MWs, you should probably figure out how to use Item Plando so your games aren't in each other's worlds, logically hardlocking the AP MW: https://archipelago.gg/tutorial/Archipelago/plando_en 

Template plando_items:
- items:
      AM2R: true
      Cave Story: true
      Metroid Dread: true
      Metroid Fusion: true
      Metroid Prime: true
      Metroid Prime 2 Echoes: true
      Metroid Samus Returns: true
    force: false
    from_pool: true
    world:
      - MWgame1
      - MWgame2
      - MWgame3<img width="299" height="497" alt="image" src="https://github.com/user-attachments/assets/bf2e80d8-517a-464e-a9e7-4e023c6358b0" />
