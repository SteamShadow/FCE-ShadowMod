Shadow's Plus Mod for FortressCraft: Evolved! (Single User Mode ONLY)



Installation:

   Just copy the Shadow.PlusMod folder to:
       %appdata%\..\Local\ProjectorGames\FortressCraft\Mods
 directory
       or run the Install.bat file which will do so for you.

   Turn on the mod on the "Select Mods" Screen for any world you want to use them.



Uninstalling the mod:

   Collect all mod machines in the world.

   Deactivate the mod on the "Select Mods" Screen for each world.

   Delete the Shadow.PlusMod folder from the installation directory Mod folder.



Description:

   Enhancements of 2 existing machines for Single User GamePlay Mode...



AutoBuilder Plus Mk1-Mk4:

   It has the same basic functionality as the AutoBuilder.

   It adds the ability to place any Voxel None Machine Block into the World.

   It adds the ability to set a Width for Item/Block placement based on Tier level
:
      (Mk1: 1 - Mk2: 1,3,5 - Mk3: 1,3,5,7,9 - Mk4: faster/efficient Mk3).
      (Build Distance is still set to 256 max for each Tier).

   Replacement option: Blocks will only be replaced when 'ON' (ORES/OBJECTS/Entities are never Replaced)


   Reset option: Restart building when a path is Blocked



   Useful for Creating Ceilings, Floors or Wall Blocks



   Required Research:

      T1 assist Machines, AutoBuilder
      T1 Power, T2 Power, T3 Power based on tier Level of Mk1-Mk4



   Known Issues:
      
      Server Support is not implemented.

      AutoBuilder Mk1-Mk4: Unable to change the color of the entire machine (only the shuttle is a different color).
	  
      AutoBuilder Mk1-Mk4: Unable to Hide Research until the AutoBuilder has been built and Scanned
	      
 
Conveyor Filter Plus Mk1:
   
   It has the same basic functionality as the Conveyor Filter.

   
   It adds the ability to "NOT" the selected Filter Category.

   
  
   Useful for creating Filtering chains with a Category/Not Category using a Storage Hopper and 2 Conveyor Filters Plus.

   

   Required Research:

      T1 assist Machines

   Known Issues:
      
      Server Support is not implemented.

      I implemented my own StorageHopper routines for Counting/Deleting Inventory:
        (Some properties and methods that I needed in StorageHopper are private - No RoundRobin deletion).
      To update the StorageHopper's Text Panel 
I call ToggleHopper twice:
        (forces a Text update value to set along with some 
other cleanup without changing the original vacuum status).
 

      When the New StorageHopper API's are available I plan on rewriting parts of the code to make it more efficient.



Warning: 
   It is my 1st attempt at modding a Game!

 
   PLEASE Backup your world before using this Mod. 
   Single User Mode ONLY - No Server Network Support
   Did I mention: PLEASE Backup your world before using this Mod. 

History:
   
   V1: Initial public release



A Special Thanks to "Tricky!" for help understanding Storage Hoppers and Inventory concepts within the game!




