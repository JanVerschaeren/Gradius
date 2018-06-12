# Gradius

1) Download both the "resources" map and the "gradius" file on an Ubuntu machine.
2) Install SFML
3) Make the file executable (with chmod +x or by right clicking then picking properties -> permissions -> allow execution)

The game should be executable now.


Having a different processor might cause the game not to start or crash. 
Im not allowed to make the source code public. 
Email me at jan.verschaeren@hotmail.com if you need a copy of the source code to compile it yourself.

To compile yourself: go into the "build" folder the run the "CMake .." command, then enter "make install".
Your executable should be in the bin folder now.

# Features
  - bullets have range
  - bullets carry a bit of the ships velocity
  - ships have health bars
  - infinite and random border blocks
  - multiple power ups
  - window manager
  - options menu
  - victory and game over screen
  - everything is read in from xml files

# Missing features
  - exeption handeling on game breaking xml file manipulations
  - no sound
  
  
