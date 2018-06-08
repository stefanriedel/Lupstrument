# Lupstrument
This is a project within my the "Music Informatics Seminar" at the Institute of Electronic Music and Acoustics, Graz. 

The idea behind this project was to build a multichannel looper instrument
that can be played solely by acoustic and haptic feedback. The interface
design doesn’t contain any visual feedback and enables the performer to
play entirely by ear.
Furthermore, the instrument integrates concepts of the musique-concrète
technique that was developed by Pierre Schaeffer in the 1950s. [6] In
contrast to a traditional looper pedal, this instrument allows drastic live-
modifications to the recorded and looped sound material. The possible
modifications include selecting the start and end of the loop within the
recorded audio material, as well as playing the loop reversed and at altered
speed.
Key to the concept is a proper monitoring system that lets the performer
pre-listen to loops and their live-modifications.
The concept has been realised with the open-source hardware platform Bela
[1], with software being developed in the computer music language Pure
Data. [2]

The _main.pd file is the top layer which shows the all inputs and outpus as they are layed out in my hardware version of this patch. The looper core is contained in loopclip.pd.

[1] https://github.com/BelaPlatform/bela-hardware
[2] https://en.wikipedia.org/wiki/Pure_Data
