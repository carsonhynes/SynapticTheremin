All Code for this Project was Developed at HackMIT 2013 by myself, Nick Grippo, Robert(Nick) Hannum, and Arya Boudaie.

A Synaptics Forcepad was used to create a theremin type instrument. The coordinates output by the device, x, y and f, correspond with the position and pressure of fingers on the device. For our implementation, the x, y and f coordinates corresponded with the musical note, volume, and octave played, respectively.



The notes that can be played are mapped to the major pentatonic scale to make improvisation over chords easier.

The Synaptics Forcepad API was writted in C++, and the MIDI library we used was created for Python. We linked the two using a singular text file to act as output for C++ and input on Python.

The note being played and the octave were displayed on screen through Visual Python, a 3D graphics module for Python.

Given a slightly longer amount of time, it was planned to export the notes played as the 5 most significant bits in an array and the octave be represented by the 3 least significant bits. This array was to be created in Python and exported to the Arduino interface, where it would translate into a pattern of 5 LEDs being lit according to the notes, and one of three colors on a Tri-LED being lit based on the octave.

