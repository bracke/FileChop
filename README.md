# FileChop

FileChop is a frontend for GNATchop and therefore requires GNATchop to present in the run path.

GNATchop takes a file and searches through that file for compilation units which are placed in separate files.

NOTE: this app is a RISC OS app.

# Frontend use
 
## Setup window

	Icon|      			Action/Meaning        |               Default
	----|              ---------------		  |               -------
	Sourcefile    |    This is the path of source file (mandatory, typed or dragged)   |     nil    
   Target         |   Where the files are placed (typed or dragged) |      nil           
   Source_Ref.    |   Generates Source_Ref. pragmas     |     off
   Comp. Script   |   Generates a compilation script     |    off
   Overwrite      |   Existing files are overwritten     |    off

## Setup Menu

   Entry        |     Action/Meaning             |          Default
   -----        |     --------------              |         -------
   Command line |  Any other options can be entered. (See the manual for full details.)  |   auto
                     

## Display (FileChop) Window
This window is opened automatically and displays any output produced by GNATchop.

## Display (FileChop) Menu
From this menu you can pause/continue and abort GNATchop.