# LqrControlTutorial
This repository contains the code for the following Youtube tutorial: 
- https://www.youtube.com/watch?v=KqdP0DVZ-lQ

## Getting Started
Run the script [main.m](https://github.com/PatrickSuhm/LqrControlTutorialOctave/blob/master/main.m) to start the simulation and the script [deriveOde.m](https://github.com/PatrickSuhm/LqrControlTutorialOctave/blob/master/deriveOde.m) to symbolically calculate the system equations of motion.

## Prerequisites
You will need GNU Octave and two additional packages, to run the scripts:
- https://www.gnu.org/software/octave/
- https://octave.sourceforge.io/control/
- https://octave.sourceforge.io/symbolic/

## Notes
You can also use Matlab to run the scripts. You need to slightly modify them, however. Delete "pkg load control" in [main.m](https://github.com/PatrickSuhm/LqrControlTutorialOctave/blob/master/main.m) and "pkg load symbolic" in [deriveOde.m](https://github.com/PatrickSuhm/LqrControlTutorialOctave/blob/master/deriveOde.m), since Matlab doesn't know these commands.

### Author
Patrick Suhm
