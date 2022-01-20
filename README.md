# ImpellerFreeVibration

## Description
This project deals with a lumped parameter model of an impeller blade, but the approach could be applied to any cyclic symmetric rotating structure.
Each blade is represented as a point of mass having one degree of freedom (rotatation around impeller axis). The code solves the eigenvalue-problem 
to obtain the natural frequencies and the eigenvectors which are normalized to the first eigenvector. The displacements are drawn and animated with 
the VPython library.
The notebook contains a function called "ImpDisp" created for drawing two superposed impeller blades in different colors.
Assuming harmonic motion of the vibration, the angular displacement is associated to each blade with the amplitude equal to the corresponding value 
of the eigenvector of the mode to be displayed.

## How to run
In order to run the notebook the VPython library needs to be installed using pip. 

## Credits
Motahar Seyed Mohammad & Tavella Alexander


