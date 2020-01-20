# QT960-Schematics
A more readable clone of the QT960 Schematics

This GIT contains converted OrCad schematics using both OrView, a vaporware OrCad Schematic viewer and printer by a company called uMace, and a schematic rasterizer called SCH2BMP for OrCad 3.x created by Robert Andrea Rossi. Without both these programs, this conversion would not be possible.

The schematics here can also be downloaded on the Intel-Vintage-Developer site located here: http://intel-vintage-developer.eu5.org/DESIGN/I960/SCHEMS/QTSCH.HTM

However, this file lacks the "PALEQNS" folder which was found on the dumped QT960 v2.1 disk contained within a physical evaluation kit. 

The "PALEQNS" folder has not been converted yet but there are plans to do so.

Also note to interface with the QT960 Eval board NINDY or MON960 needs to be compiled and uploaded to the board's EEPROMS.

Please note that compiling the included NINDY requires CTOOLS, which is curently a "lost media."

A specially modified version of CTOOLS 5.0 for Unix can be found here: https://www.cs.cmu.edu/afs/cs/project/cmcl/link.vcnectar/gnu960/

Note that both compiling this modified CTOOLS would require modifications to undo specifics added by CMU and that in the Release Notes it clearly states "The NINDY monitor is no longer supported. MON960 is the only supported target." The source code for MON960 is also a "lost media."