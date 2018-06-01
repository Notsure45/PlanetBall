# Planet Ball 
## Version 0.2.0 BETA
### *A planetary golf-like game built on LÖVE 0.10.2*

Comments in the code attempt to explain any functions. Contact for clarification/updating comments.

#### OVERVIEW:
A golf game. A player must combine all 'balls' on screen in order to win.
Balls are naturally attracted to eachother, and may start orbits around eachother.
Players can click/touch on the screen to create gravity wells to which the balls are attracted to.
Lower time spent using/creating these wells will result in a higher score.

##### FEATURES
- [x] Objective Ball System
- [x] Collision System
- [x] Gravity
- [x] Levels
- [x] Level select
- [x] Menus
- [x] Some good design
- [x] Trails
- [x] Touch controls!
- [x] Camera Panning
##### TODO:
- [ ] Add pre-made graphics
#### SPECIFICS:
Balls have their own:
* Color
* Mass
* Radius
* Position
* Velocity
* Acceleration
	
A player can create an invisible 'ball' upon interaction[touch/click] with the game.
It has no color, velocity, acceleration, or radius, and has a constant mass; This is to encourage planning of the use of one's clicking.
Think of it like an interactor, balls come towards your mouse

#### RELEASE HISTORY:

0.0.0: initial collision/physics work, never released

0.0.1: removed spin mechanic, fixed collisions crashing game; code cleaning

0.0.2: fixed bug where gravity did not properly attract; code cleaning

|a: fixed other gravity bug

0.0.3: Added rudimentary GUI, added pause function, fixed combining, made trails better.

0.0.4: Added levels and JSON support for levels, added asset handler

0.1.0 Fixed and added JSON support for menus, buttons now execute functions.
	  Also fixed screen burn issue with balls, they now fade appropriately
	  Fixed Phenonmenom where ball would rocket to high speeds when mouse clicked inside it
	  Made collesion detection slightly smoother
	  Offically in BETA :D (Shouldn't be long, just have to cobble together assets)
	  
0.1.1 Added Rudementary Camera, fixed screen burning phenomenom
 |a: fixed compatibility with windows
 
0.2.0 Finished the Camera
	  Added touch control.
	  Improved UI.
	  Added a function to get absolute distance between two vector-valued tables