Shadow's Plus Mod for FortressCraft: Evolved! (Single User Mode ONLY)

Installation:
   Just copy the Shadow.PlusMod folder to the %appdata%\..\Local\ProjectorGames\FortressCraft\Mods
       directory or run the Install.bat file which will do so for you.
   Turn on the mod on the "Select Mods" Screen for any world you want to use them.

Uninstalling the mod:
   Collect all mod machines in the world.
   Deactivate the mod on the "Select Mods" Screen for each world.
   Delete the Shadow.PlusMod folder from the installation directory Mod Folder.

Mod Description:
   Enhancements of 2 existing machines for Single User GamePlay Mode...

AutoBuilder Plus Mk1-Mk4:
   It has the same existing functionality as the AutoBuilder.
   Required Research:
       T1 assist Machines, AutoBuilder
	   T1 Power, T2 Power, T3 Power based on tier Level of Mk1-Mk4

   It adds the ability to place any Voxel None Machine Block into the World.
   It adds the ability to set a Width for Item/Block placement based on Tier level
   A Replacement option is added - Blocks will only be replaced when 'ON' (ORES/OBJECTS/Entities are never Replaced)

   A Reset option is added to restart when a path is Blocked

   Useful for Creating Ceilings, Floors or Wall Blocks

Conveyor Filter Plus Mk1:
   It has the same existing functionality as the Conveyor Filter.

   It adds the ability to "NOT" the Filter Category.

   Useful for creating Filtering chains with a Category and a Not Category using a Storage Hopper and 2 Conveyor Filters Plus.

   Conveyor Filter Plus Mk1 does not have Network Support for MultiPlayer Mode.

Warning: PLEASE Backup your world before using this Mod. It is my 1st attempt at modding a Game!

 Version History:
   V1 - Initial public beta release

   Known Issues:
      Server/Client Support is not implemented other than what was in the base classes used.

      AutoBuilder Mk1-Mk4: Unable to change the color of the entire machine (only the shuttle is a different color).
	  AutoBuilder Mk1-Mk4: Unable to Hide Research until the AutoBuilder has been built and Scanned
	       If anyone knows how to accomplish this or require a specific machine to be scanned before the Research is available
		   would be helpful, rather than requiring a research point!
      
      ConveyorFilter Plus Mk1: 
           I had to write my own Storage Manipulation routines for NOT Filtering.
           Some properties and methods that I needed were private.
           Because of this the only way I figured out how to trigger an update to the StorageHoppers Text Panel 
               was to call the ToggleHopper twice which forces a Text update value to set along with some 
               other cleanup.
  
      When the New StorageHopper API's are available I plan on rewriting parts of the code to make it more efficient.

A Special Thanks to "Tricky!" for help understanding Storage Hoppers and Inventory concepts within the game!

