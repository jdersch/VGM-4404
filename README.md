# VGM-4404
A VGM Player for the Tektronix 4404 AI Workstation

This is a quick 'n dirty VGM player for the Tektronix 4404 AI Workstation.
The 4404 has a TI 76496 PSG for some reason, and what better way to 
put it to use than by playing chiptunes?  Well, that's what I 
thought at 2am anyway.

This program plays VGM files that use the PSG; all other commands 
and metadata are ignored.  It also requires the input VGM files be 
uncompressed.  Sorry.

As the timebase for the PSG driver in Uniflex is 1/60th of a second, 
PAL files and files that require a different timebase will play back
incorrectly.  Life is hard.

Multiple files may be played in succession, but in that case the
files will not be looped.

(c) 2020 j. dersch.  
