 Night Hunters 1.51	http://www.planetquake.com/nighthunters

 Credits:
	Main team
		Programming/System/Servers BatMax  	(batmax@fragit.net)
		Programmer DingBat  			(dingbat@fragit.net)
		Instigator/graphics/people/dox BatCat	(batcat@fragit.net)
	Original
		Majoon
	Additional
		Predator Model, Conan David Hunter	(conan@aw.sgi.com)
		Demo(s), FaTaL				(soulwound@hotmail.com)
		IR Model, Maru-Ki			(jdcooke@ionsys.com)
	Beta testers, HeadStone, BatBios, Mercenary, ComBat, SpiderBat, FragU,
		MeerKat, CrunchyBat, Neo-Phyter, Justin the Cynical, Lorus, BaTTy,
		Krenshala, DarkZenith, InitializE, Captain Kirk, Neo-Phyter, Niv
 
	Special Mention..
		for NH Home pages PlanetQuake.com	http://www.planetquake.com
		for progaming do's/don'ts Qdevels	http://www.planetquake.com/qdevels


 ----

 Extract this archive to your QUAKE2 directory

 Which should create a path of "Quake2/nhunters"

 Two Q2 demos are included showing gameplay and tips, demo1, and some of the predators
 jumping abilites, demo2. (*note, predators jumping can exceed demo recording rates!)

 GameSpy (www.gamespy.com) or other Q2 server browsers can be used to find servers.
 There is also a servers page off the NH home page on PQ.

 To play Night Hunters under Mission Pak 1 (Xatrix), see the NH-Xatrix-readme.txt
 in the Xatrix directory

------------------------------------------------------------------------------------
 Quick Starts: (Windows/NT)
	Play Online:
		Double click "nhstart.bat" file, go to menu MutliPlayer/Join Server

	Server for you and your buddies:
		Double click "nhlisten.bat"

	Dedicated Server:
		Edit nhserver.cfg (hostname, passwords, public..)
		Edit motd.txt, keep in mind minimum 320x200 screen
		Edit info.txt, use the current one for size guide
		Double click "nhded.bat"

****Note Fussy or Power Users edit autoexec.cfg and merge your autoexec.cfg
------------------------------------------------------------------------------------
Quick Starts: (Linux)
	Play Online:
		Execute "nhstart" file, go to menu MutliPlayer/Join Server

	Server for you and your buddies:
		Execute "nhlisten"

	Dedicated Server:
		Edit nhserver.cfg (hostname, passwords, public..)
		Edit motd.txt, keep in mind minimum 320x200 screen
		Edit info.txt, use the current one for size guide
		Execute "nhded"

****Note Fussy or Power Users edit autoexec.cfg and merge your autoexec.cfg
------------------------------------------------------------------------------------

 Files:
 pak0.pak	all custom sounds, icons, models

 autoexec.cfg   contains default key binds and adresses for NH servers
		players will need to merge with your baseq2/autoexec.cfg

 nhstart(.bat)	quick start for users to play online
 nhlisten(.bat)	quick start server for you, and your buddies to connect to
 nhded(.bat)	quick start a dedicated server

 nhserver.cfg	main server configuration file.  Make sure
		you modify the following settings right away:
		hostname, admin, public ..etc.

 motd.txt	What is displayed when a person joins the server

 info.txt	What is displayed in the menu when a user accesses the Menu/INFO.
		(*note, first line is a guide and NOT displayed)
		(*note, must fit inside inventory window)

 nhdemo.txt     demo 'readme'
 demos/
 demo1.dm2      demo of gameplay and some tips, click nhstart(.bat)
 demo2.dm2	demo of predators jumping abilities on q2dm1
		(*note, predators jumping can exceed demo recording rates!)

-----
	(default key) Current features:
              
	G Flashlight
		Available to both Marine and Predator  
		Marine's light will illuminate themselves (RED) as well as
		where they are looking (GREEN)
		Predator's light only illuminates where it is looking (BLUE)

	Infrared
		Available to both Marine and Predator  
		Pick up IR Goggles and see all warm bodies Glow
		(replaces Quad and Invulnerability on all maps)

	F Flare
		Available to Marine only  
		A standard weapon, throw it like Hand Grenade, given a few at the
		start, no more can be picked up

	Q Report (* new!)
		Available to Marine only  
		Will report where you have seen the predator from, like the CTF command

	V Gunscope
		Available to Predator only  
		Switchable Zoom setting 1X 2X 4X and 8X

	O Overload (*new!)
		Available to Predator only  
		Uses 2 Rockets and does double damage

	E/R Teleport
		Available to the Predator only  
		 Two modes: 
		  -Panic, hit RECALL key only in first few seconds of predator's
		    first start and re-respawn 
		  -Escape, ANCHOR some place safe (or not) then RECALL to it

	Air Acceleration
		Available to the Predator only  
		Predator is given extra jumping abilities

	Regeneration
		Available to the Predator only  
		Predator will regenerate Health and Ammo at a slow rate

	Weapon Restrictions
		Marine: None, may pick up anything  
		Predator: Uses modified Rail Gun and Rocket Launcher
		Can not pick up any weapons, ammo or armor

	M Menu
		Brings up menu directly
		TAB twice also brings up menu


 The above bindings are included in the autoexec.cfg file in the client.
 You can also type 'setup' at the Quake2 console after connecting to a
 Night Hunters server to have the above keys automatically bound. 


--------------
	Rules: 

 -Predator is killing Marines..

 -All Marines are hunting the predator

 -The predator is 66% transperant, not invissable, allowing it to blend into backgrounds. 

 -The new predator has its own model now, "nhpred". Marines can freely be any Player Plugin Model (PPM). 
  The server Admin can also set the default Marine to -one- model/skin to anything he has or leave it free.  
  (You may need to check the "Menu/Models Used" when you join, to see what is being used) 
  (Keep in mind some player models may look like the predator model and cause all kinds of trouble) 

 -There is only ONE predator, and it is selected:  
  Either at random on Game start or the current Predator leaves the game, if a marine  
  kills the predator, then the marine becomes the predator.  

 -When using the flashlight, space marines can be heard (by a little buzzing sound) 
  and seen (they glow from the power being used). Unfortunately, you can't go 
  through the level without using the flashlight. 
  (The Light is GREEN and they glow RED) 

 -The predator's light scope is much dimmer than the marine's, but you cannot  
  see the predator when it's using it (just try it, you'll see). (Its Light is BLUE) 

 -The predator's gunscope works like a regular gunscope, zooming in on an area.  
  The marines do not have access to this. (Its a toggle, 2x, 4x and 8x, then back 
  to 1x, normal) 

 -The predator makes no sound while running, and cannot be hurt no matter
  how far it falls. (Falls and Jumps do make a sound) 

 -The predator gets 5 health, 1 slug, and 1 rocket every 10 seconds.  

----------
  Scoring: 

 -Marines score 3 points when they kill the predator, and then becomes the
  predator himself.  

 -If a marine kills another marine, they lose 1 frags.  

 -If a marine kills too many marines then two penalties are progessively invoked! 
  1. Kill a few too many and you start to GLOW, default is 3. 
  2. Kill more marines and you get auto-kicked, default is 4. 
    -Both- are based on your LAST 5 minutes, if you killed your
    first 4min's ago you will glow for 1min. 

 -The predator scores 1 frag per kill (of marines).  

 -The predator loses 1 frag when killed.  

 -If the predator kills himself, he loses 2 frags.  

 -If anyone's score goes below -10, they get kicked.
  (They must be doing something horribly wrong!) 

 Supporting Web Page http://www.planetquake.com/nighthunters





----------
Some additional server notes..


 To start a DEDICATED server, use the following command line:

 For Linux:
  ./quake2 +set game nhunters +set dedicated 1 +exec nhserver.cfg


 For win32 (Windows95/98/NT):
  quake2.exe +set game nhunters +set dedicated 1 +exec nhserver.cfg

***Note: If you run more than one server, make sure you '+set port 27911', like so..
  ./quake2 +set game nhunters +set dedicated 1 +set port 27911 +exec nhserver.cfg



 To start a LISTEN server (so you can play the game on the same computer and other
 users connect to you), use the following command line:

 For Linux:
  ./quake2 +set game nhunters +set deathmatch 1 +exec nhserver.cfg


 For win32 (Windows95/98/NT):
  quake2.exe +set game nhunters +set deathmatch 1 +exec nhserver.cfg
	
-----------
 Server Variables not in config file and not recommended to alter for
  game balance or other quirks. 
	 (Note: server variables are case sensitive)

  <<<space for variables we used for game testing but not in the .cfg>>>

// A custom pred model has a problem in that the 1st player on to server will
// not DL the custom model on the server, he will see grunt.
// Anyone that does not have the various DL flags on will not get the model either,
// and will see the grunt.

set predator_model "nhpred"	// Model for predator
set predator_skin "nhpred"	// Skin for predator

set flare_bright_time 12 	// Time of "bright" phase of flares.
set flare_dim_time 6		// Time of "dim" phase of flares.
set flare_die_time 12		// Time of "burnout" phase of flares.

set teleport_health 0		// If pred health is less than this, it cannot teleport.

set IR_marine_fov 75		// Marine fov when using IR goggles.

set init_marine_weapon "flare"	// Initial weapon for marines. 
				// If you screw it up, defaults to flare.

set maxtime 300			// 5 mins for maxmarinekill

// Initial predator inventory
set predator_max_rockets 50 
set predator_max_slugs 20 
set predator_start_rockets 10
set predator_start_slugs 5
set predator_start_health 200

set predator_model "nhpred"	// Model for predator
set predator_skin "nhpred"	// Skin for predator

set allow_predator_overload 1 	// Allow predator to overload rocket launcher.
set predator_overload_cost 2 	// Ammo it costs to fire in overload mode.

set marine_safety_time 12 	// Marine safety mode turned on.
set predator_safety_time 0 	// Predator safety mode turned on.

set use_NH_scoreboard 1 	// 1=Night Hunters custom scoreboard.  0=default Quake2
