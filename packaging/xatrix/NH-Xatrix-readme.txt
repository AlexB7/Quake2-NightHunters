 Night Hunters 1.51 Xatrix	http://www.planetquake.com/nighthunters

 To play Night Hunters Xatrix (NHX), you must own and have installed 
 Quake2 Mission Pack 1 - The Reckoning by Xatrix (http://www.xatrix.com)

 Please read the file readme.txt in the nhunters folder before trying
 the Xatrix version of Night Hunters as this readme only covers Xatrix specific
 issues.

 The purpose of Night Hunters Xatrix is to be able to play Night Hunters using
 the Xatrix maps, and the new Xatrix weapons.  Other than that, it's identical to
 regular Night Hunters.

 To play Night Hunters Xatrix you **MUST**:
 ------------------------------------------

 Copy the nhunters/pak0.pak to xatrix/pak1.pak	(NOTE: do NOT overwrite
						 your Xatrix pak0.pak!!!)

 That's it!  Connect to a server and you'll be set.  

 NOTE: Because the NH pak file contains a new conback, you will always see
 the Night Hunters conback when you play Xatrix.


 To run a Night Hunters Xatrix SERVER you MUST:
 ----------------------------------------------

 Copy the nhunters/pak0.pak to xatrix/pak1.pak (note: do NOT overwrite
	 					your Xatrix pak0.pak!!!)
    
 You must understand how Quake2 works with mods to understand how to use Night Hunters
 Xatrix.

 New files are placed into your quake2/xatrix directory:

 gamei386.nhx.so
 gamex86.nhx.dll
 nhxlisten.bat
 nhxlisten 
 nhxded.bat
 nhxded
 nhserver.cfg		(contains a few changes to regular config file)

 You will also have the following files which are part of the regular Xatrix mission pak:

 gamei386.so
 gamex86.dll

 Quake2 will always load gamei386.so (Linux) or gamex86.dll (windows) from the mod directory
 so to play NHX, you must rename your existing gamei386.so or gamex86.dll to something else.
 I suggest you do the following:

 copy gamei386.so gamei386.xatrix.so
 copy gamex86.dll gamex86.xatrix.so

 Now you have a backup of your original Xatrix files.

 To run a NHX server:

 copy gamei386.nhx.so gamei386.so	(for Linux)
 copy gamex86.nhx.dll gamex86.dll	(for windows)

 Then start the server as described below.  To go back to the regular Xatrix game:

 copy gamei386.xatrix.so gamei386.so	(for Linux)
 copy gamex86.xatrix.dll gamex86.dll	(for windows)

------------------------------------------------------------------------------------
 Quick Starts: (Windows/NT)

	Server for you and your buddies:
		Double click "nhXlisten.bat" in the xatrix directory

	Dedicated Server:
		Edit xatrix/nhserver.cfg (hostname, passwords, public..)
		Edit xatrix/motd.txt, keep in mind minimum 320x200 screen
		Edit xatrix/info.txt, use the current one for size guide
		Double click "nhded.bat" in the xatrix directory

------------------------------------------------------------------------------------
 Quick Starts: (Linux)

	Server for you and your buddies:
		Execute "nhXlisten" in the xatrix directory

	Dedicated Server:
		Edit xatrix/nhserver.cfg (hostname, passwords, public..)
		Edit xatrix/motd.txt, keep in mind minimum 320x200 screen
		Edit xatrix/info.txt, use the current one for size guide
		Execute "nhded" in the xatrix directory

------------------------------------------------------------------------------------

 If you are already running a Xatrix server and ALSO want to run a NHX server, then
 you have a problem because you have to change the gamei386.so/gamex86.dll file.

 There IS a solution!

 Download Game-Loader from the Night Hunters file section (http://www.planetquake.com/
 nighthunters).  Game-Loader will allow you to specify which DLL to load on the Quake2
 command line, so you don't have to rename files to switch between them.


Optional reading:
********************************************************************************************
* The standard Quake2 plays from the quake2/baseq2 directory.  Baseq2 contains all the     *
* standard Quake2 single player maps, and the q2dm1-q2dm8 maps, the players, sounds,       *
* hud icons etc.                                                                           *
*                                                                                          *
* When you play another mod such as Mission Pack 1, Rocket Arena, Night Hunters or         *
* Lithium for example, the mod is run from a new directory inside of your quake2 folder.   *
* For example, Night Hunters is run from the nhunters directory.                           *
*                                                                                          *
* While playing ANY mod, the baseq2 directory is ALWAYS available.  That is why you can    *
* play q2dm1 in Night Hunters and Lithium.  Type PATH at the Quake2 console and you will   *
* see baseq2 listed.                                                                       *
*                                                                                          *
* Here's the problem:  The ideal way to setup Night Hunters Xatrix would be to place the   *
* needed files in a folder called NHX under Quake2.  If we did this, then Quake2 would NOT *
* find the Xatrix pak file which contains the maps, sounds, new weapons etc for Xatrix.    *
* Because of this, the gamei386.so (or gamex86.dll), Night Hunters pak file, nhserver.cfg, *
* info.txt, motd.txt etc must be placed inside of the Xatrix folder.  The REAL problem is  *
* replacing the gamei386.so (or gamex86.dll) in your Xatrix folder would prevent Xatrix    *
* from working in single player mode!                                                      *
********************************************************************************************

