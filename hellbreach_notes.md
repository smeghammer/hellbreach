# Hell breach

# Play
Doom2, single player only.

# Levels
Currently includes:

MAP15
  - map 16
  - map 17 
  - map 31
 

## secret level
 - secret level is inaccessible area from a later level (TODO)
 - marble hallway?
 - large arena outside this, that is inaccessible
 - COPY this and use as part of another level
     - make sure the secret level copy is not accessible from this other level


## TODOs

### MAP14:
An intro to map 15 - city-style? use same textures as start of MAP15.

### MAP15:
 - sewer exit lift texture to metal
 - More spider demons? 
 - SSG somewhere?
 - ambush from map15 canyon by exit?
 - Block blue barrier above with tree
 - light/floor re brutal in entry room (is too bright with Brutal)
 - check baron trap by megasphere 
 - baron trap - adjust escape stair
 
### MAP16

#### canyon



#### cave system
 - secret access from behind start secret
 - stalagtites of pale colour like craters
 - switch for soul sphere in secret bit somewhere
 - allow to SEE caves for last crater
 - monsters behind big ass metal doors in cave 
    - use this as motif for last section
    - add taster for this on last bit of 4th crater section?
 - have extensive cave system on multiple levels. 
 - access to last level only via this?
 - switch puzzle somewhere?
 - big arse doors open to release barons / cacos?
 - make uppe canyon more maze-like, and SMALLER. 
    - big fucking gate/barrier with switch in maze guarded by knights?
 - block most of flat upper area
 - cracks on floor in front of baron doors
 - climbable block landscape down to last area.
 - crater bigger and red concentric around it?
 - cracks?
  - OK - use the red variation of the stone texture, fade into the far corner to the BFDoors.
  
####hexen-style doors:
 - type=12
 - SR
  - 0,16,150 (tag, speed, delay)
 
 -784, -688 + 288 = -496,-400
 
crossing for iron cage:
 - fake floor:  -1192
 -fake ceiling: -1200
 
 
### MAP17
 - move current (unfinished) to MAP18(?)
 
### MAP17 (new)
Make a dark, lava-cracked descending cave coming from the end of Hells Canyon. Reveal a BIG FUCKING DOOR that is the entrance to Hell...

linked door:
control tag: 132
door tags: 128


	Sector_SetLink (193, 176, 0, 3);		//
	Sector_SetLink (193, 191, 0, 3);		//Links lowering/rising   platform: Supply Storage
	Sector_SetLink (193, 192, 0, 3);		//



 - switch for red key cage also opens bars by bridge?
 - switch somewhere that overlooks canyon that will open multiple doors on barrachs (to be designed). Yellow key in here, but releases shit-tonnes of monsters into the canyon...
 - verticlaly stacked cacos etc in spiral stair space, and chaingunners etc placed ON stairs via Z co-ord (NOTE: relative to real floor not absolute grid z-coord)
 
 Single-trigger script!!
  - need to trigger a lowering ONCE if there are multiple linedefs calling the same thing:
  - need to have a boolean triggered=true/false and only action if actioned=false, otherwise do nothing...
  
  
  
 
 
 
** Final area:** 
Jutting out iron thing...
cut out:
1 - floor: -1280, ceil: -1190(work out)
2 - floor: -1472, ceil: -1190(work out)
 
 canyon:
 - check/adjust cave heights

**skull key sequence**

It doesn't matter which order you do it - getting one is not dependent on getting another beforehand.
W
 - move yellow key to be visible in iron box thingie
 *first key:*
 **RED (-4960, 1500 )** 
  - entrance at -4080,2560 OR -3625, 2100
  - protected by BoH
  - switch (-4050, 1500) opens cage around red key and drops bars at -3560, 1560
 **BLUE (-1880,1130 )**
 [need switch to OPEN door and switch to lower bars (TODO)] 
  - add bars at  -2890, -525 - Need switch for these
   - change door at -2050, 860 to switch. TODO: Need switc for this as well (inside)HK room at -2100, -500 
      - new room and switch at -2650, 640 (TODO)
 **YELLOW (in iron box)**
  - needs to be VISIBLE form above
  - bars on far side of bridge open from obscured passageway opposite
     - move soul sphere to somewhere else, remove some of the bars, make sure you can SEE the bars from here (possibly light them better?)
      
 ARSE! I can get into the yellow key iron box by going IN to the tunnel at -1200,-500: Resolve by adding bars here that are flagged as 138 as well
  - STEPS to get back up to start area so you can do the yellow switch if missed!!
  - yello key big arse door does not open at all!
  - align wall textures whjere iron wall is breaking

 - found sector that blocked in one of the caves
 - add better directions to various caves - some are quite difficult to see.
 - adjust light levels?
 - add many more monsters
 	- use monster traps with dribble feed (1-at-a-time)
 	
  - adjust monster balance?
  - PLAYTEST!!!
  
  block exit from iron box!!
  
 - stuck mancubus at lower middle cave
 - light levels on cave exit
 - complete floor wrincles here too!
 - more ammo 
 - additional weapons (SSG, RL)
 more MONSTERSjust generally hiding in caves etc.
 - more in final exit
 - link exitr domes to killing the barons?
     - TID=101
     - 2616, 2617, 32
 - move initial SG to round the corner
 
### MAP18
 - See above
 
### MAP31
 
 
### GITHUB!!!
OK.


