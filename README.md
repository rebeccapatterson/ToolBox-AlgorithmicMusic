# ToolBox-AlgorithmicMusic
Algorithmic Music Composition Project Toolbox starter code

Full instructions at https://sites.google.com/site/sd16spring/home/project-toolbox/algorithmic-music-composition

This program creates a 16 bar blues solo that is played to a longer backing track. Each time the code is ran, a new solo is created and saved over the old .wav file.

To make the solo a different length, change the range in line 58.  Since each lick is only half a bar, the solo will be range/2 bars long.

Before running the code, be sure that you have Nsound and matplotlib.pylab installed.

To run the code and create a solo, type 
	$ python blues_solo.py
 in the terminal.  To listen to the solo, type 
	$ cvlc slow_blues.wav
To quit cvlc, type
	$ ctrl c
