# [[Vehicle Characteristics]]
## Handling
---
- decided by size, shape, control system, mass and awkwardness
- baseline handling is 0
- agile ships add BOOST to piloting for positive values
- slow ships add SETBACK to piloting for negative
## Speed
---
- abstract max speed of the vehicle
- can always go slower than max
- 0-5
	- speed 0 is stationary
	- speed 1 slow moving walker or transport ship
	- speed 5 tie fighter or cloud car
### Atmospheric & sublight speed
- atmo operation is slower than space
- 1 speed in atmo is slower than 1 speed in space
## Silhouette
---
- abstract size
- factor heavily into scale
- used to calculate difficulty of attacking differently sized targets
- 0-10
	- 0 is smaller than a human (starship component, jawa, astromech)
	- 1 is human
	- 3-4 starfighters/light freighters
	- 10 largest stations and starships
### Personal Scale Vehicles
- all personal ranges are CLOSE in planetary range
- 2 vehicles in CLOSE range could be anywhere from ENGAGED to EXTREME
### Person Vehicle Scaling
- vehicle weapons, armor and hull trauma is equal to 10pts of personal scale
- conversely, 10pt of personal scale damage is equal to 1pt of vehicle scale damage
- +50 to critical injury roll
- if personal weapon firing on ship, must exceed ARMOR to inflict critical injury
- all planetary scale weapons have BLAST quality, damaging all targets in SHORT range
## Hull Trauma Threshold
---
- Wound threshold for vehicles
- 1 HTT = 1 Wound Threshold
## System Strain Threshold
---
- exceeding strain threshold causes system overloads, shutting down until repaired/rebooted
- negatively effects performance and disables occasionally
- suffers strain from:
	- crew activities
	- excess THREATs
- System strain cant be recovered by ADVANTAGE
	- only recovered through crew actions
	- reduced by 1 for every full day spent without suffering more strain
## Protection
---
- amalgam of maneuverability, hull durability, shields, thickness etc
- divided into DEFENSE and ARMOR
### Defense
- deflect/reduce damage
- each defense adds 1 SETBACK to any attack
	- each FAIL can greatly reduce/negate damage
	- THREATs lessen critical hits
#### Silhouette & Defense Zones
- have number of defense Zones dictated by silhouette
	- <= 4, 2 DEFENSE ZONEs (forward and aft)
	- >= 5, 4 ZONES, (forward, aft, port, starboard)
- each ship has preset zone ratings
	- set by computer system & shield generators
- can re-route defense from one zone to another
	- move 2pt of forward defense to add 2 pt to aft defense
	- lasts until you change it back on your turn
- each DEFENSE ranking adds 1 SETBACK to attack
### Armor
- SOAK.  have to beat this score to deal damage

---
---
# Starship Systems
## Escape Pods
- Ships size >= 4 have escape pods
- can keep occupants alive for 5 days.
## Sensors
- Operate in Passive or Active
- Passive
	- low power, see everything around ship up to max range band.
	- no skill check
- Active
	- can see 1 range band farther than max in the ships firing arc
	- requires EASY(1d8) COMPUTERs check
		- modified by radiation, atmo, terrain or jamming
---
---
# Starship Weapons
---
![[Pasted image 20260303212337.png]]
## Fire Arcs
- each ship has 4 fire arcs (forward, aft, port, starboard)
- depending on mount of weapon, can cover one or multiple arcs
	- Fixed weapons only cover 1 arc
	- Turret mounted weapons can cover any arc
- Some ships of Dorsal and Ventral arcs. These are exclusive
# Vehicle Combat
## initiative & Slots
- all PCs & NPCs roll initiative (SIMPLE 0d8 COOL or VIGILANCE) 
- works the same as normal combat
- per CHARACTER not per VEHICLE
## Piloting
- piloting Character must make relevant PILOT check for vehicle when called for
- to control vehicles, take actions, avoid disaster
## Small Craft
- 1 maneuver, 1 action (or 2 maneuvers) on pilots turn
- can fly and fight aboard ship, or fly entirely
- describe actions, embellish with lots of flair, make skill checks to resolve actions
## Capital Craft
- silhouette >= 5
- very abstract
- 1 maneuver, 1 action (or 2 maneuvers) on pilots turn
- each crew member can use actions & starship maneuvers to use weapons, sensors, move and engage in combat
- only act with those pertinent to encounter, ignore the rest
## 238 Maneuvers
- Starships with <= 4 silhouette get 1m 1a, or 2m.
	- Ship gains 2 System Strain for additional pilot only maneuver
	- if only 1 pilot, pilot also gains 2 strain
- ships >= 5 ONLY get 1 maneuver
## Action
### Combat
1. Declare attack & targets
2. Assemble dice pool
3. Pool results, deal damage
4. Resolve Advantage & Triumph
5. Resolve Threat and Despair
6. reduce damage, apply hull trauma, apply crits
---
---
# Stellar Terrain
- when passing treacherous obstacle, PILOTing check, even in MANEUVER would not require one
	- difficulty based on speed & silhouette
- PILOTING check DIFFICULTY is higher of SPEED or 1/2 SILHOUETTE(round up)
	- Higher value is # of dice
	- lower value is # of upgraded dice
## Hazards
- if action is difficult, add 1 SETBACK(black D6)
- see table for hazard setback dice amount
# Chase
- Mostly narrative, skill checks resolve outcome
- determine starting distance, if ground vehicles, may use personal scale ranges
- make COMPETETIVE PILOTING/ATHLETICS check
	- difficulty depents on terrain/circumstances
 	- clea open space is SIMPLE(0dif)
	- IF pursuer wins: Close in by 1 range band
 	- IF chased winds: escape distance by 1 range band
  	- if winner is faster speed, distance += difference in relative speeds
- Chase ends when reaching ENGAGED range, or past EXTREME range
- if during combat, make check at beginning of round
---
---
# 248 Taking Damage
- [[System Strain]] vs [[Hull Trauma]]
## [[Hull Trauma]]
- threshold of sturdiness/build quality
- when taking damage greater than armor, converts to hull trauma.
- when exceeding hull trauma, 1 of 2 things happen:
	- [[Silhouette]] <= 3 and of no importance, explode and kill pilot.  Can also be disabled by GM
	- [[Silhouette]] >=4, or smaller with a [[PC]] on it: 
		- Takes [[Critical Hit]].  
		- Ship systems shut down, reverts to Emergency power
		- Sublight drives die.
		- Lifeless hulk, being evacuated
- crew may attempt repairs to disables ship with [[Hard]] [[Mechanics]] check
	- on success, reduce [[Hull Trauma]] by 1.
	- takes penalties:
		- speed = 1
		- handling = -3
		- weapons inoperable
		- any further damage generates 1 [[Critical Hit]]
			- 1d100  + 30
- Effects continue until repaired at drydock
## [[System Strain]]

## 248 [[Collisions]]
2 types of collisions
- [[Glancing Blow]]s (minor collision)
	- all vehicles take 1 [[Critical Hit]]
		- Roll = 1d100 - (ships defense * 10)
	- if 0, effect is nullified.
- [[Head-on Hit]]s (major collision)
	- all vehicles take 1 [[Critical Hit]]
		- Roll = 1d100 - (ships defense * 5)
- larger ships may  ignore collisions with small ships

