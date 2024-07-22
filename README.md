# Signalis_APManual
A Manual apworld for usage with the Archipelago randomizer.

This was made as a part of development for adding SIGNALIS as a proper apworld. **This currently will not work on console versions of SIGNALIS, due to the debug menu being inaccessible on those platforms.** 

This manual was tested with the latest SIGNALIS version 1.2 KRÄHE. It should work with all versions theoretically, but I suggest updating to 1.2 for intended usage for the debug menu.

**What has been randomized?**
- Usage of the Radio Module
- All item pickups (puzzle items, door keys, ammo, healing items, etc.)

Notes are not randomized. Neither are items that you acquire as a result of combining items (such as Butterfly Key or Revolver). The Earth Key is also not randomized, only the Blank Key is.

**The debug console**
This manual is intended to be used in tandem with SIGNALIS' built-in debug console. To access the debug console:
1. Load into a save
2. Press F7 (nothing will happen)
3. Type `ausruinen` (nothing will happen, there is also no visual indicator of the letters being typed)
4. Hit Enter
5. If successful, four small dots will appear at the top left of your screen. Elster may or may not take damage.

These steps must be performed every time the game .exe is restarted.

Once in the debug menu, the commands `give`, `remove`, and `boxall` are used when checking Locations in-game and receiving Items in Archipelago.
- The `give` command is to give Elster an Item received via Archipelago. ex: `give microfiche` gives the Aperture Key.
- The `remove` command is to remove an item from Elster's inventory. Meant to be used when receiving an item from a Location, but Archipelago has not sent you that Item yet. ex: `remove rifle` will remove the Rifle after picking it up.
- The `boxall` command will move all items currently in Elster's inventory into the storage box system found in save rooms.

**Additional notes**
For the complete item list of Archipelago Items and their in-game equivalents to use with the debug menu, see item_list.md.

For more info and debug commands regarding Rotfront's flesh doors, see rotfront_flesh_walls.md.

For more info and debug commands regarding item pickup amount changes across game difficulties, see difficulty_changes.md.

Since the Broken Airlock Key and Adhesive Tape are essentially SIGNALIS' equivalent of a randomized Morph Ball from Super Metroid, if playing in a multiworld, it is recommended to not progress until you receive both of these items so you can exit the Penrose Crash site and access the first Save Room within Installation Aeon. Otherwise, 
